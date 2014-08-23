Project
=======
* This file describes how the runanalysis.R script works.
1. Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder as "Data".
2. Make sure the folder "Data" and the runanalysis.R script are in the working directory.
3. Use source("runanalysis.R") command in RStudio. 
4. You will find two output files are generated in the current working directory:
  - mergeddata.txt: contains a data frame called cleanedData with a dimension of 10299*68.
  - datawithmeans.txt: contains a data frame called result with a dimension of 180*68.
5. Use data <- read.table("datawithmeans.txt") command in RStudio. 