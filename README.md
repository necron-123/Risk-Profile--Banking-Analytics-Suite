# Risk-Profile--Banking-Analytics-Suite
This project aims to demonstrate how banks and financial institutions can utilize data visualization to minimize lending risks and better understand their clients' financial behavior.

Project Overview
By analyzing client profiles, account balances, and banking timelines, this Power BI dashboard allows banking institutions to make data-driven decisions. For example, the dashboard helps predict if an applicant is likely to repay a loan, which aids in the loan approval process. It also tracks total deposits, credit card balances, and processing fees to provide a complete view of a client's financial standing.

Dataset Description
The project relies on a relational dataset containing various client and banking details.  The data is spread across multiple interlinked tables, including: Banking Relationship, Client-Banking, Gender, Investment Advisor, and Period. 
The tables are connected using primary and foreign keys.

Data Preparation and Cleaning
Before building the dashboard, the raw data was transformed to create new, actionable metrics:
Engagement Timeframe: A new column was created to categorize how long a client has been with the bank (e.g., "< 5 Years", "> 20 Years"). 
Engagement Days: Calculated the exact number of days a client has been with the bank, from their join date to the present day.  
Income Band: Categorized clients' estimated income into brackets ("Low", "Mid", and "High") for easier demographic analysis.  
Processing Fees: Assigned numerical fee values (e.g., 0.05, 0.03) based on whether a client's fee structure was labeled High, Mid, or Low.

Key Metrics Analyzed (KPIs)
The dashboard calculates and visualizes several Key Performance Indicators (KPIs):
Total Clients: The overall count of distinct clients in the banking system. 
Total Loan: The combined sum of standard bank loans, business lending, and credit card balances. 
Total Deposit: The combined sum of standard bank deposits, savings accounts, checking accounts, and foreign currency accounts.
Total Fees: The total revenue generated from account setup and maintenance charges.  
Specific metrics are also tracked individually, such as Business Lending, Checking Account Amounts, and Savings Account Amounts

Key Insights & Future Applications
Strategic Growth: The data reveals that private banks hold a larger number of clients. Competitor banks can use this insight to adjust their strategies. 
Demographic Lending: The dashboard can quickly identify which nationalities hold the highest bank loans. 
Account Distribution: It provides a clear breakdown of how investor funds are distributed across different account types (savings, checking, foreign currency). 
