# Databel: Telecom Customer Churn Analysis

## 📌 Project Overview
This project focuses on identifying the drivers behind customer attrition for **Databel**, a telecommunications provider. Using a multidimensional dataset, I analyzed customer behavior, demographics, and service plans to uncover why customers leave and how to improve retention.

## 🛠️ Tech Stack
* **Tools:** SQL, Tableau (or Excel), Data Visualization
* **Analysis Focus:** Churn Prediction, Customer Segmentation, Revenue Impact
* **Dataset Structure:** 29 Columns (Snapshot based, No time dimension)

## ❓ Problem Statement
The primary challenge for Databel is maintaining a stable customer base.
* **Unidentified Drivers:** It was unclear if churn was driven by pricing, demographic factors, or specific plan types.
* **Financial Risk:** Churning customers directly impact the `Total Charges` (cumulative revenue), making retention a financial priority.
* **Static Data Complexity:** Analyzing a database snapshot required finding correlations within a single point in time rather than over a historical trend.

## 💡 Solution: The Churn Dashboard
I developed an analytical framework to categorize and visualize customer data:
1. **Churn Label Analysis:** Separating the "Yes" vs. "No" churn groups to find commonalities.
2. **Demographic Mapping:** Analyzing how age, location, and gender impact loyalty.
3. **Plan Evaluation:** Investigating "Premium Plans" to see if higher-tier services correlate with better retention or higher churn.
4. **Revenue Analysis:** Using `Total Charges` to identify the "Value at Risk."

## 📊 Dataset Highlights
* **Primary Key:** `Customer_id` (Unique identifier)
* **Target Variable:** `Churn Label` (Yes/No)
* **Key Measure:** `Total Charges` (Sum of all monthly charges billed)
* **Dimensions:** Demographics, Contract types, Premium Plan details

## 🏁 Strategic Conclusion
The project provides Databel with the insights needed to move from reactive customer support to **proactive retention**. By profiling the high-risk customer segments identified in this analysis, the business can implement targeted loyalty programs and plan adjustments to reduce the overall churn rate.
