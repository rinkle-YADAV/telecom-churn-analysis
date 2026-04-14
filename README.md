# telecom-churn-analysis
Telecom churn prediction using customer usage &amp; service data. EDA + ML models (Logistic Regression, Random Forest) to identify at-risk customers.
# Customer Churn Analysis using Python

## Problem Statement
Predict which telecom customers will churn so the business
can intervene early and reduce revenue loss.

## Dataset
Telco Customer Churn — Kaggle | 7,043 rows | 21 features

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Steps
1. EDA and churn distribution analysis
2. Data cleaning and encoding
3. Feature engineering (ChargesPerMonth, HighRisk, TenureGroup)
4. Logistic Regression + Random Forest
5. Evaluation: Accuracy, Recall, AUC, Confusion Matrix

## Results
Accuracy: ~80% | AUC: ~0.84 | Churn Recall: ~72%

## Key Insights
- Month-to-month customers churn 3x more
- Tenure under 12 months = highest risk
- Recommendation: annual plan discounts + tech support bundles

## Business Impact
10% churn reduction = approx Rs 40–60L saved annually
