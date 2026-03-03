# IBM Telco Customer Churn Analysis

##  Project Overview
The primary objective of this project is to analyze customer data to identify patterns and key drivers of churn (e.g., contract types, service choices, and demographics). This diagnostic analysis provides data-driven recommendations to improve customer retention strategies.

##  Key Findings
Based on the exploratory analysis of over 7,000 customers:
* **High-Risk Groups:** Churn is significantly higher among fiber optic users, senior citizens, and customers on month-to-month contracts.
* **Churn Correlations:** Lower tenure (under 10 months) and high monthly charges (> $70) are strong indicators of potential churn.
* **Retention Drivers:** Services like "TechSupport" and "Online Security" are correlated with lower churn rates.

## Tools & Methodologies
* **Language:** Python
* **Libraries:** Pandas (Data Manipulation), NumPy (Numerical Analysis), Matplotlib & Seaborn (Data Visualization).
* **Workflow:**
    * **Data Cleaning:** Handled missing values in `TotalCharges` (imputed based on monthly charges and tenure) and converted binary categories to 1/0 for numerical analysis.
    * **EDA:** Conducted univariate and bivariate analysis to detect imbalances and correlations.

## Recommendations
1. **Contract Incentives:** Offer discounts or bundles to move month-to-month customers toward long-term contracts.
2. **Targeted Support:** Focus retention campaigns on new customers (tenure < 1 year) and high-cost fiber optic users.
3. **Value-Added Services:** Promote "TechSupport" and "Online Security" add-ons to high-risk groups to increase stickiness.

## Project Structure
* `IBMTELECO_CUSTOMER_PRACTICE_ANALYSIS.ipynb`: The complete analysis including code, visualizations, and documentation.
* `Telco-Customer-Churn.csv`: The raw dataset used for the analysis.