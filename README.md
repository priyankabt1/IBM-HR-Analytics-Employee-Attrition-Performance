# IBM-HR-Analytics-Employee-Attrition-Performance 🚀

# Project Overview
This project aims to analyze employee attrition using machine learning models. By identifying key factors contributing to attrition, the project provides actionable insights for HR teams to improve retention and employee satisfaction.

# Dataset
* IBM HR Analytics Employee Attrition Dataset
* Contains features such as age, job role, work-life balance, overtime hours, and more.
  
# Objective
* Predict employee attrition (Yes/No) based on available features.
* Identify the most significant factors contributing to employee attrition.

  Tools & Libraries Used
* Programming Language: Python
* Libraries:
1) Pandas, NumPy (Data Manipulation)
2) Matplotlib, Seaborn (Data Visualization)
3) Scikit-learn (Machine Learning Models)
4) XGBoost, CatBoost, Gradient Boosting
5) SHAP (Model Explainability)

  # Models Implemented
# Model	                     Accuracy (%)     AUC Score (%)
Random Forest Classifier	   92.5	            97.5
Gradient Boosting	           92.3	            96.5
XGBoost Classifier	         92.5	            96.8
CatBoost Classifier	         92.7	            97.1

# Key Highlights
Feature Engineering:

* Created derived features like "Overtime Hours" and "Job Role Satisfaction Index" to uncover hidden patterns in data.
Model Explainability:

* Used SHAP (SHapley Additive exPlanations) to interpret model predictions and identify critical factors impacting employee attrition.
Insights Gained:

* Key factors influencing attrition include:
  Job Satisfaction
  Work-Life Balance
  Overtime Hours
