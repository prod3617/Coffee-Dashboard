# Excel Data Analysis

##  Coffee Sale Analysis

### Table of Contents

- [Project Description](#project-description)
- [Data Source](#data-source)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Tools](#tools)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
  

### Project Description
The project aims to create a comprehensive dashboard to analyze coffee sales. We have analyzed the coffee sales by period and region. We have also found the top 5 customers. We have also provided various filter options to do deep-dive analysis.

![Coffee Dashboard Image](Coffee%20Dashboard.png)

### Data Source
- Coffee orders Data: The data can be found in the file "coffeeOrdersData.xlsx". We have multiple sheets in the file as orders, customers, and products.

### Tools
- Excel: For data cleaning and visualization.

### Data Cleaning and Preparation
 We have checked the data for the null values and duplicate values and removed the duplicate record. As the orders table is the factual table, we have inserted some of the columns in the table by using DAX formulas like xlookup, index, and match functions.

### Exploratory Data Analysis
Performed some exploratory data analysis to find some information about key questions like
- How much sales are happening in each region?
- Who are the top 5 customers?
- How is the sale happening across the period for all the coffee types?

### Data Analysis
To find the key answer to the question, we have created the pivot table and analyzed the data.

### Results/Findings
- The United States is selling the maximum coffee.
- Arabica is the most sold out coffee.
