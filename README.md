# Introduction
Case study 3 was developed to automate data analysis for current engineering tests. The values and attributes have been modified with multiple factors and name change to protect the company. This Jupyter Notebook will be able to accommodate a different numbers of data files, print required graphs and provide context to the results.

# History
These test are not only engineering tests but can also be qualification and validation and verification (V & V) and can range from 2 hours to days. The output of the data acquisition would output a .txt file. The engineer would then create an excel file, load the .txt file in each sheet, aggregate the data into one sheet, and explore the data set. After exploration and analysis, visualization is created for the final report. This process usually would take from 1-1.5 weeks on average or longer depending on the amount of data and results to review and how often excel would crash from the size of the data.

# Problem
* Manually importing .txt file to excel, 1 file per sheet
* Manually aggregating the data
* Performing new exploratory analysis in conjunction with the same exploration and analysis every time
* Excel crashing from just trying to open the file with graphs

# Solution
* Jupyter Notebook can produce the importing, aggregating, and analysis all in one run
* Reducing the number of repeated steps in excel every time
* Reducing the need for excel and downtime from crashes
* Can produce immediate graphs or reports for presentation faster than excel
* Reducing the number of excel files needed