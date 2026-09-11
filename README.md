# Telco Customer Churn Analysis — ABC Communications Ltd

Data analytics case study completed as part of the AnalystLab Africa Data Analytics Internship Programme (Week 1: Business Analytics Case Study).

## Business Problem

ABC Communications Ltd, a telecommunications provider, is losing subscribers to competitors at a significant rate. This project investigates why customers churn and translates the findings into retention recommendations for management.

## Dataset

Telco Customer Churn Dataset (IBM sample, via Kaggle)
Source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
7,043 customer records with demographics, account details, subscribed services, and churn status.

## Tools Used

Python, pandas, matplotlib, seaborn, Jupyter Notebook

## Key Findings

- **Contract type is the strongest churn driver.** Month-to-month customers churn at roughly 4x the rate of one-year contract holders and 15x the rate of two-year holders.
- **Churn is front-loaded onto new customers.** Most attrition happens in the first few months of tenure; customers who pass that window are far more likely to stay long term.
- **Fiber optic customers churn disproportionately.** They make up 44% of the customer base but 61% of all churned customers, despite being the premium product.
- **Support add-ons reduce churn.** Customers without OnlineSecurity or TechSupport churn about 3x more than those with it.
- **Electronic check payers churn roughly 3x more** than customers on automatic payment methods.

## Repository Contents

- `ABC_Communications_Churn_Analysis.ipynb` — full data inspection and analysis notebook
- `Business_Understanding_Report.docx` — business problem and industry context
- `Dataset_Inspection_Report.docx` — data quality and cleaning summary
- `Churn_Analysis_Presentation.pptx` — summary presentation

## About

Completed by Peter Thuo Muiruri, Data Analyst
