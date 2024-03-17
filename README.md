# Customer-Churn-Analysis

## Project Overview
This project delves into understanding the key reasons behind customer churn at a telecommunications company. Utilizing PySpark for in-depth data analysis, we aim to uncover factors influencing customer retention strategies, providing actionable insights for the company to improve customer loyalty and reduce churn rates effectively.

## Objectives
* To identify churn rates among different customer groups based on their monthly charges and tenure.
* To explore the relationship between monthly charges and churn rates.
* To assess how the source of invitation influences customer churn.
* To identify predominant sources of referrals.
* To enable the company to take proactive measures in retaining customers likely to churn.

## Data Description
The analysis is based on the Telco_customer_churn.csv and Telco_customer_churn_status.csv datasets sourced from the IBM accelerator catalog. These datasets contain comprehensive information about customers, including demographics, service subscriptions, billing information, and churn status, encompassing 7014 observations and 44 variables.

## Methodology
Our analysis workflow employed PySpark to leverage its distributed computing capabilities, allowing us to handle large volumes of data efficiently. The process included:

* Data Acquisition and Loading
* Data Preprocessing and Transformation
* Feature Engineering and Selection
* Exploratory Data Analysis (EDA)
* Model Development and Validation
* Interpretation of Results

## Key Findings
* Higher monthly charges and shorter tenure are significant predictors of churn.
* The churn rate increases with higher monthly charges, indicating a possible price sensitivity among customers.
* The source of invitation has a significant impact on churn, with customers acquired through merchant collaborations showing higher churn rates.
* The "High Spend Short Tenure" group has the highest churn rate, suggesting newer customers with higher monthly charges are more likely to leave.

## Recommendations
* Revise pricing strategies for high-spending customer segments.
* Evaluate and potentially revamp merchant collaboration programs.
* Incentivize referrals from family members, the leading source of new customers.
