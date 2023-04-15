Financial Analysis Shiny Web Application
This Shiny web application allows you to analyze your financial transactions by visualizing monthly income and costs along with their trends. You can upload a CSV file containing your transactions, and the app will display a line graph and a table with relevant statistics.

Features
Upload a CSV file containing transaction data
Line graph displaying monthly income and costs trends


Prerequisites
Before running the app, make sure you have R and the following packages installed:

shiny
readr
dplyr
lubridate
ggplot2
You can install the packages in R or RStudio using the following command:


Copy code
install.packages(c("shiny", "readr", "dplyr", "lubridate", "ggplot2"))

Usage
Save the Shiny app code provided above in a file named app.R.
In R or RStudio, set the working directory to the folder containing the app.R file using the setwd() function:

Copy code
setwd("path/to/your/folder")
Run the app using the following command:

Copy code
shiny::runApp("app.R")
The Shiny app will open in your default web browser. Upload a CSV file containing your transactions by clicking the "Upload CSV File" button. The CSV file should have the following columns:
Date
Account
Description
Category
Tags
Amount

After uploading the file, the app will display a line graph showing monthly income and costs trends, along with a table containing relevant statistics.


License
This project is released under the MIT License.
