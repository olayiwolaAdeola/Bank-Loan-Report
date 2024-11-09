# Project Overview
A Report to monitor and assess our bank's lending activities and performance which aims to provide insights into key loan-related metrics and their changes over time.
Data Source
Financial Loan: The primary dataset used for this analysis is the "financial_loan.csv" file, containing detailed information about each loan made by the bank. 

## DataSet
### Tools Used
•	Microsoft SQL Server

## Data Cleaning/Preparation
In the initial data preparation phase, I performed the following tasks:
•	Data Loading and Inspection with the MS SQLServer
o	It was used to first import and edit the data
o	The "emp_title" had a VARCHAR(50) but was modified to VARCHAR(100) to contain more texts.
o	The "id" was ticked to be the Primary Key
o	Any/All fields having NVARCHAR were modified to VARCHAR
o	The "total_payment" had SMALLINT but was reset to INT to contain maximum values
o	The "loan_amount" was also set to INT

## Exploratory Data Analysis
EDA involved exploring the financial loan data to answer key questions, such as:
A) KPIs
1.	What's the Total Loan Applications using the following:
o	Current Month-to-Date loan applications (MTD)
o	Previous Month-to-Month (PMTD) to track changes.
2.	Total Funded Amount using:
o	Current Month-to-Date total funded amount (MTD)
o	Previous Month-to-Month (PMTD) to track metric changes
3.	Total Amount Received using:
o	Current Month-to-Date (MTD) to know our total amount received
o	Previous Month-to-Month (PMTD) to track metric changes
4.	Average Interest Rate Using:
o	Current Month-to-Date(MTD) to know our average Interest Rate
o	Previous Month-to-Month (PMTD) to track metric changes
5.	Average Debt_to-Income_Ratio(DTI): Evaluating the average DTI for our borrowers helps us gauge their financial health.
o	Current Month-to-Date (MTD) Average DTI
o	Previous Month-to-Month (PMTD) to track metric changes
•	*Note: Both Current and Previous Months calculations would help get the Month-over-Month (MoM) trends
B) What are the Good Loan Vs Bad Loan?
C) What is the Loan Status Overall?
### The following would be considered along:
a) Loan By Monthly Trends

b) Loan By States

c) Loans By Employee Length

d) Loan By Purpose

e) Loans by Home Ownership
## Recommendations
Based on the analysis, with respect to the metrics used, also with the Monthly Trends, the following actions are recommended:

•	The bank should focus on knowing the circumstances surrounding February period to know if to continue giving out loan to applicants since there was a dip in applications which would as well affect the return rate (Amount Received), and January being the first month of the year with relatively low applications .

•	Hot periods to give out loans due to applications/demand is from the month of July through December.

•	Employees with length of over 10yrs had higher returns compared to others with lower year length. This might be due to experiences, loyalty, or salary earned. Loans should be given more to this group if those conditions might be the case. Else, those with 2yrs length looks promising to give loan to since their return rate is higher than those having 3yrs and 4yrs of length.

•	Renters had the highest application rate, but their return rate (Amount Received) came second to those with Mortgage which initially came second in overall applications. Therefore, Loans should be given to both but more to those with Mortgage.

•	Marketing and Promotions: Targeted marketing campaigns or special loan offers during specific months might drive application numbers.

## Limitations
•	Since the Economic conditions weren't stated during the loaning periods, it made it somewhat difficult to know why some applicants did poorly in their return rate

•	Also, there was no column stating "death_rates" to enhance or help our analysis have better understanding of the situation.


