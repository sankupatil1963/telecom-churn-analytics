# Business Requirements Document (BRD)

## 1. Project Overview

### Project Name
Telecom Customer Churn Analytics

### Business Problem

The telecom company is experiencing customer churn, which can negatively
impact recurring revenue and customer lifetime value.

Management wants to understand customer churn patterns and identify
customer segments that are more likely to leave the company.

The analysis will help the business and customer retention teams
understand the major factors associated with customer churn.

---

## 2. Business Objectives

The primary objectives of this project are:

- Calculate the overall customer churn rate.
- Identify customer segments with high churn rates.
- Analyze churn by contract type.
- Analyze churn by customer tenure.
- Analyze churn by monthly charges.
- Analyze churn by payment method.
- Analyze churn by internet service.
- Identify important patterns associated with customer churn.
- Estimate the monthly revenue currently at risk because of churned customers.
- Provide actionable insights that can support customer retention strategies.

---

## 3. Key Business Questions

The analysis should answer the following questions:

1. What percentage of customers have churned?
2. Which contract type has the highest churn rate?
3. Does customer tenure affect churn?
4. Which payment method has the highest churn rate?
5. Which internet service has the highest churn rate?
6. Do customers with higher monthly charges churn more frequently?
7. Which customer segments have the highest churn risk?
8. How much monthly revenue is associated with churned customers?
9. What business actions could help reduce customer churn?

---

## 4. Key Performance Indicators (KPIs)

| KPI | Definition |
|---|---|
| Total Customers | Total number of customers in the dataset |
| Churned Customers | Number of customers who have churned |
| Churn Rate % | Churned customers divided by total customers |
| Monthly Revenue at Risk | Sum of MonthlyCharges for churned customers |
| Average Tenure | Average number of months customers have stayed |
| Average Monthly Charges | Average monthly charge across customers |
| Churn by Contract Type | Churn rate for each contract type |
| Churn by Payment Method | Churn rate for each payment method |
| Churn by Internet Service | Churn rate for each internet service |

---

## 5. Stakeholders

The primary stakeholders for this analysis are:

- Marketing Head
- Customer Retention Team
- Business Manager
- Customer Service Team
- Data/Analytics Team

---

## 6. Data Source

The project uses the IBM Telco Customer Churn dataset available
through Kaggle.

The dataset contains customer demographic information, services,
contract information, billing information and customer churn status.

The exact number of rows and columns will be validated during the
data profiling and data quality stage.

---

## 7. Key Data Fields

Important fields expected to be used in the analysis include:

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges
- Churn

---

## 8. Analytical Scope

The analysis will cover the following areas:

### Customer Demographics
- Gender
- Senior citizen status
- Partner
- Dependents

### Customer Tenure
- Tenure distribution
- Tenure groups
- Churn by tenure

### Services
- Internet service
- Phone service
- Online security
- Online backup
- Device protection
- Tech support
- Streaming services

### Contract and Billing
- Contract type
- Payment method
- Paperless billing
- Monthly charges
- Total charges

### Churn
- Overall churn
- Churn by customer segment
- Churn by contract
- Churn by payment method
- Churn by service
- Churn by tenure

---

## 9. Data Quality Requirements

Before analysis, the dataset should be checked for:

- Missing values
- Duplicate customer records
- Invalid data types
- Invalid numeric values
- Inconsistent categorical values
- Missing or invalid total charges
- Duplicate customer IDs

All identified data quality issues should be documented and resolved
before creating the final analytical dataset.

---

## 10. Technology Stack

The project will use the following technologies:

| Technology | Purpose |
|---|---|
| JIRA | Requirement and task tracking |
| Git | Version control |
| GitHub | Source code and documentation |
| Oracle XE | Database |
| SQL Developer | SQL development |
| SQL | Data validation and KPI analysis |
| Python | Data cleaning and analysis |
| Pandas | Data manipulation |
| NumPy | Numerical analysis |
| Matplotlib | Data visualization |
| Seaborn | Exploratory data analysis |
| Power BI | Interactive dashboard |
| Markdown | Project documentation |

---

## 11. Deliverables

The project will deliver:

1. Business Requirements Document
2. Data Dictionary
3. Validated analytical dataset
4. Oracle database table
5. SQL data quality queries
6. SQL KPI queries
7. Python data cleaning notebook
8. Python exploratory data analysis notebook
9. Power BI customer churn dashboard
10. Project README
11. GitHub repository
12. Jira project and task tracking

---

## 12. Expected Dashboard

The Power BI dashboard should provide:

- Total Customers
- Churned Customers
- Churn Rate
- Average Monthly Charges
- Average Tenure
- Churn by Contract
- Churn by Internet Service
- Churn by Payment Method
- Churn by Tenure
- Interactive filters/slicers

---

## 13. Expected Business Outcome

The project is expected to help the business:

- Identify high-churn customer segments.
- Understand major churn patterns.
- Identify customers or segments requiring retention efforts.
- Understand revenue currently at risk.
- Support data-driven customer retention decisions.

---

## 14. Assumptions

- The dataset is representative of the customer population being analyzed.
- Customer ID is treated as a unique identifier.
- Churn value indicates whether a customer has left the company.
- Monthly Charges represent the customer's recurring monthly billing amount.
- Data quality issues will be handled before final analysis.

---

## 15. Project Workflow

The project will follow the workflow below:

Business Requirements
        ↓
Data Collection
        ↓
Data Profiling
        ↓
Data Quality Checks
        ↓
Oracle Database
        ↓
SQL Analysis
        ↓
Python Cleaning & EDA
        ↓
Business Insights
        ↓
Power BI Dashboard
        ↓
Documentation
        ↓
Final GitHub Repository