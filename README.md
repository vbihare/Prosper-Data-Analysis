# Prosper Loan Data Analysis
## About the dataset:
This project is on a data set from Prosper, which is America’s first marketplace lending platform, with over $7 billion in funded loans. 
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, 
borrower employment status, borrower credit history, and the latest payment information, etc. The main purpose of this project is to summarize the characteristics of 
variables that can affect the loan status and to get some ideas about the relationships among multiple variables using summary statistics and data visualizations.

The dataset can be download here: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000

## Summary of the Analysis:
- There were many variables that were related to the Borrower's APR, hence using the correlation matrix I got to have a better understanding of it.
After analyzing each variables. Borrowers's APR, Borrowers's score, rating, available bank card credit and creditscore were found to be negatively correlated to Borrower's APR. Adding that that, borrower' Scores (given from 0 to 11) 
gave the strongest negative relationship with borrower's APR.
- Borrowers with different letter ratings were also analyzed. It came out that borrowers with the lowerest rating(HR) received higher APR percentage, and borrower with high rating A(A) received lowers APR percentage. 
This differentiate groups of people in terms of APR received based on their rating and scores.

## Key Insights
After exploring all possible variables related to BorrowerAPR. ProsperScore has the strongest relationship with Borrower's APR (negatively correlated). 
Scatter plot and Heatmap were also created to find out that ProsperScore and BorrowerAPR were negatively correlated. 
The plot created multiple scatter plots (BorrowerAPR vs ProsperScore) on different letter ratings. The plots showed the lowerest rating(HR) of borrowers received the 
highest APR percentage, and borrowers with highest rating (AA) received the lowerst APR percentage.

## Resource
- Prosper data dictionary[https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0]
- pandas documenation
- matplitlib documentation
- seaborn documentation
- Example Project from Udacity
