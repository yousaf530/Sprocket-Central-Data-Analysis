# Problem Statement

Sprocket Central Pty Ltd is a medium size bikes & cycling accessories organisation. It needs help with its customer and transactions data.The organisation has a large dataset relating to its customers, but their team is unsure how to effectively analyse it to help optimise its marketing strategy. So they have approached out team to provide a solution for them

### Data Sets Provided
* Customer Demographic 
* Customer Addresses
* Transactions data in the past 3 months

### Requirements
* #### Module 1
Identify data quality issues and draft email to client about those issues
* #### Module 2
Ppt presentation to outlines our approach to identify the 1000 customers Sprocket Central Pty Ltd should target based on data. 
Explain the three phases:  
    * Data Exploration 
    * Model Development 
    * Interpretation.
* #### Module 3
    * Create Dashboard
    * Specify who Sprocket Central Pty Ltd' should be targeting out of the new 1000 customer list
  


## Solution

The solution process will follow three steps:

    1. Data Cleaning and Exploration
    2. Building a Data Model
    3. Data Visualization and Interpretation

### Module 1
### Data Issues


Dear Client, following are the recommendations our team has identified regarding current data quality concerns in your data set.
#### Customer Demographics
1) Kindly standardize the gender column values. i.e Male, Female inplace of M, Male, Female etc (Consistent Values) <br> 
2) Kindly avoid adding "default" column with random data/invalid Data. <br>
3) Kindly record "Date of Birth" in proper date format. i.e (MM/DD/YY) <br>

#### Transactions
1) Kindly record "product_first_sold_date" in proper date format i.e. (MM/DD/YY) <br> 
2) Kindly avoid placing empty values in columns. Use NULL either. <br>
3) Customer ids of non-existing clients in the Transactions dataset should be removed or proper customer data should be recorder.

### Module 2

The process followed in Module 2 are available in Module_2.ppt.

### Module 3

After Exploration of Customer Data and development of model, a Dashboard and summary report is generated to keep track of existing and to target new potential customers based on existing data.

Google Data Studio Dashboard: <a href='https://datastudio.google.com/u/0/reporting/6c9248b0-ab9c-4fb6-b300-7fb65e31aa00/page/yYs8B' target='_blank'>Link</a>
