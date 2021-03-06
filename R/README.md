# Getting started in R

 1. If needed, install the [bigrquery](https://github.com/hadley/bigrquery#authentication) package.
 
   ```
    # The currently released version 0.3.0 does not yet have the parameter
    # to use Standard SQL instead of Legacy SQL, so we install from github.
    library(devtools)
    install_github('rstats-db/bigrquery')
   ```

 2. From the R prompt set the working directory and run the script:

   ```
   setwd("path/to/getting-started-bigquery/R")
   source("getting-started.R")
   GettingStarted("your-project-id")
   ```

# Troubleshooting

* If you see an `Error: Access Denied` response from the `GettingStarted` function,
  that means your Project ID is invalid. Follow the instructions in the top level
  [README](https://github.com/googlegenomics/getting-started-bigquery)
  to get a valid Project ID.
