Title : End-to-End Customer Churn Analytics & Prediction Engine

Project Overview :
Customer churn is a major problem in the telecom industry where customers discontinue their services. Retaining existing customers is far more cost-effective than acquiring new ones.
This project builds an end-to-end machine learning system to predict whether a customer is likely to churn based on their demographic details, account information, and service usage patterns.

The system helps businesses:
1.Identify high-risk customers
2.Take proactive retention actions
3.Reduce revenue loss

Objectives :
- Analyze customer behavior using Exploratory Data Analysis (EDA)
- Perform data cleaning and feature engineering
- Train and evaluate multiple machine learning models
- Select the best-performing model based on business-critical metrics
- Predict whether a customer will churn or not

Tech Skills:
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Machine Learning, EDA, Feature Engineering, Model Evaluation

Dataset
The dataset contains 1000 customer records with the following features:

1.CustomerID
2.Age
3.Gender
4.Tenure
5.MonthlyCharges
6.TotalCharges
7.ContractType
8.InternetService
9.TechSupport
10.Churn (Target Variable)

Key Insights :

- Customers with month-to-month contracts are more likely to churn
- Lower tenure customers have higher churn probability
- Higher monthly charges increase churn risk
- Contract type, tenure, and internet service are strong churn predictors

Results :

Final Model: Random Forest Classifier
Accuracy: ~99.5%

Recall for churn customers: 100%

This ensures no at-risk customers are missed
