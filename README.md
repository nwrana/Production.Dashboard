# Production.Dashboard
My first production dashboard using R-Shiny.Dashboard

The Production.Dashboard folder contains: server.R, ui.R, and a folder named 'data'
The 'data.csv' file is stored in this location. This file is updated every week.

To run the dashboard, the following commands must be loaded:
setwd("./R-Shiny Apps") #assuming your working directory is ("C:/user/Documents")
library(shiny) #load the shiny package 
runApp("Production.Dashboard") #name of folder that contains the above 3 files
