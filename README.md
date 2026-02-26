# Retail Sales Performance Dashboard
Power BI dashboard analyzing retail sales and profitability

## Project Overview
This project simulates a business intelligence dashboard built for retail leadership to monitor sales performance, profitability, and regional trends.
The Power BI dashboard analyzes:
- Sales performance
- Customer behavior
- Repeat customer %
- Customer lifetime value (CLV)
- Profit simulation (What-if parameter)
- Break-even and sensitivity analysis

## Business Problem
Retail managers need a centralized view of sales and profit data to identify underperforming regions, categories, and time periods.

## Tools Used
- Power BI
- Power Query (Data Cleaning)
- DAX (KPIs & Measures)
- Data Modelling

## Data Quality Checks
 - Found 32 products having 2 product names for a single product ID
    - Solution - Created a new prod_id for the duplicate ID, and new column named as Prod_ID
 - Missing Post Code for Burlington	Vermont
    - Solution - Imputed 05401 as post code for Burlington	Vermont
 - Post codes having 4 and 5 characters
    - Solution - Padding for all post codes to have 5 characters

## Key Insights
I) Sales Performance in 2025
  - Technology Drives Revenue but Not Margin Leadership
  - Technology shows the highest total sales contribution.
  - However, Profit Margin % appears lower than Office Supplies.

II) Customer Analysis in 2025
  - High Repeat Customer Rate (~85.9%)
  - Business relies heavily on returning customers.
  - Top 5 customers contribute significant share of total revenue.
    
## Files in This Repository
- `/dataset` → Raw dataset
- `/screenshots` → Dashboard images
- `Retail_Dashboard_Vee.pbix` → Power BI file

## Outcome
This dashboard allows decision-makers to quickly identify growth opportunities and operational inefficiencies.

## Dataset source
Kaggle
https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting?resource=download

Key Transformation
- All dates moved ahead by 7 years


