# Enterprise Pilot Analytics #

*Developed by Ritu Raj Singh*

## Project Overview

This project is developed for – Enterprise Readiness Integration & Pilot Dry-Run*.

The objective of this project is to analyze pilot performance using structured data, define measurable pilot success indicators, compare Pilot and Control groups, and present the results through an interactive Tableau dashboard.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Google Colab
* Microsoft Excel
* Tableau
* GitHub

## Project Workflow

### 1. Data Preparation

The sample dataset was prepared for enterprise pilot analytics and contained different data-quality issues such as missing values, duplicate records, inconsistent text, invalid dates, and invalid numeric values.

### 2. Data Cleaning

A complete Python data-cleaning pipeline was created to:

* Standardize column names
* Remove unnecessary spaces
* Standardize categorical values
* Convert dates into proper format
* Convert numeric fields into appropriate data types
* Handle missing values
* Remove duplicate records
* Validate percentage-based fields
* Validate response time and satisfaction values
* Validate revenue and cost values
* Recalculate important metrics

### 3. Python Analysis

The cleaned dataset was analyzed using Python to calculate:

* Total Records
* Total Requests
* Completed Trips
* Cancelled Trips
* Success Rate
* Cancellation Rate
* Adoption Rate
* Average Response Time
* Average Satisfaction
* Revenue
* Cost
* Profit
* Descriptive Statistics
* Correlation Analysis
* Outlier Analysis
* City-wise Performance
* Channel-wise Performance
* Event-wise Performance
* Rider vs Driver Analysis
* Pilot vs Control Comparison
* Pilot Success Criteria Evaluation

### 4. Tableau Dashboard

The cleaned dataset was connected to Tableau to create a consolidated enterprise pilot analytics dashboard.

The dashboard includes:

* KPI Summary
* Pilot vs Control Performance
* City Performance
* Channel Performance
* Event Type Analysis
* Performance Trend
* Pilot Success Criteria

## Key Output

The project produces a cleaned dataset, analytical results, and a Tableau dashboard that provides a structured view of pilot performance.

The analysis helps identify performance differences between Pilot and Control groups, understand city and channel performance, evaluate operational metrics, and assess the proposed pilot success criteria.

## Project Structure

text
enterprise-pilot-analytics-task20/
│
├── Sample_Dataset.xlsx
├── Cleaned_Dataset.xlsx
├── Python_Notebook.ipynb
├── Python_Analysis_Report.xlsx
├── Tableau_Dashboard.twbx
├── Dashboard_Screenshot.png
└── README.md


*Developed by Ritu Raj Singh*
