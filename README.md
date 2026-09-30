# Credit-Card-Fraud-Detection-
Credit Card Fraud Detection &amp; Analysis using Python and Power BI | Data Cleaning, EDA, Fraud Pattern Analysis, and Interactive Dashboard
Executive Summary:
This project analyzes credit card transactions to identify fraud patterns and generate business focused insights using Python and Power BI.
The prepared dataset contains 10,001 transactions, including 9,701 normal and 300 fraud transactions, resulting in a 3.0% fraud rate. Total transaction value is 722,660, with 23,063 associated with fraud.
The analysis focuses on fraud volume, financial exposure, hourly patterns, country-level patterns, transaction amounts, and V1–V28 feature differences.
Dataset Overview:
The original dataset contains 10,040 records and 35 columns before cleaning.
Identifiers: transaction_id, customer_id
Customer / Geography: customer_name, country
Time: Time
Features: V1–V28
Financial: Amount
Target: Class — 0 = Normal, 1 = Fraud
Data Preparation & Quality Checks:
Identified 39 duplicate rows
Handled 80 missing customer names
Handled 50 missing country values
Handled 40 missing Amount values
Converted fields to appropriate data types
Created Hour from Time
Standardized text fields
Validated the prepared dataset
Final prepared dataset: 10,001 records, 36 columns
Business Questions, Metrics & Business Impact:
How many transactions are fraudulent?
Metric: 300 fraud transactions out of 10,001
Impact: Measures overall fraud volume.
What is the fraud rate?
Metric: 3.0%
Impact: Measures fraud prevalence.
What is the financial exposure?
Metric: Fraud Amount = 23,063
Impact: Quantifies the value associated with fraud.
Is the average fraud amount different?
Metric: Fraud average = 76.88 vs overall average = 72.26
Impact: Provides transaction amount as a supporting fraud indicator.
Which hour has the highest fraud volume?
Metric: Hour 1 = 35 fraud transactions
Impact: Identifies periods with higher observed fraud activity.
Which hour has the highest fraud rate?
Metric: Hour 1 = 8.14%
Impact: Identifies periods with a higher observed fraud proportion.
Which countries show higher fraud rates?
Metric: India 3.21% | Canada 3.13% | USA 2.97% | UK 2.60%
Impact: Supports geographic fraud monitoring.
Which V1–V28 features differ most?
Metric: V14 1.31 | V12 1.23 | V17 1.11 | V10 0.87
Impact: Identifies features for further analytical investigation.
Power BI Dashboard Overview
Page 1 — Credit Card Fraud Detection
Focus: Fraud overview
KPI Cards
Fraud vs Normal Transactions
Fraud Transactions by Hour
Fraud Transactions by Country
Page 2 — Credit Card Fraud Pattern Analysis
Focus: Fraud pattern analysis
Average Transaction Amount: Fraud vs Normal
Fraud Amount by Hour
Fraud Rate by Hour
Fraud Transactions by Amount Band
Dashboard approach: Overview first, detailed pattern analysis second.
Business Recommendations:
Strengthen monitoring during higher observed fraud rate hours.
Use transaction amount as a supporting indicator rather than a standalone rule.
Monitor fraud volume and fraud rate by country.
Combine multiple fraud indicators for deeper investigation.
Investigate V14, V12, V17 and V10 further for advanced analytics.
Refresh the Power BI dashboard as new transaction data becomes available.
Use the prepared dataset as a foundation for future machine-learning analysis.
Tools & Technologies:
Python | Pandas | NumPy | Matplotlib | Power BI | DAX | Power Query | Jupyter Notebook
Project Workflow
Raw Data → Data Cleaning → EDA → Statistical Analysis → Power BI → Business Insights
