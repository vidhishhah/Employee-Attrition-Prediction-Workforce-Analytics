# Employee Attrition Prediction & Workforce Analytics

## Overview

Built an end-to-end machine learning project to predict employee attrition and identify factors associated with employees leaving an organization.
The project covers data cleaning, exploratory data analysis, preprocessing, model comparison, hyperparameter tuning, threshold optimization, and model interpretation.

## Dataset

**IBM HR Analytics Employee Attrition & Performance**
* 1,470 employee records
* 35 original features
* Target variable: `Attrition`

## Tools & Technologies
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Google Colab

## Machine Learning
The following classification models were compared:
* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

Models were evaluated using:
* Accuracy
* ROC-AUC
* Precision
* Recall
* F1 Score

Logistic Regression was also tuned using 5-fold cross-validation.

## Results
The final Logistic Regression model achieved:

* **ROC-AUC:** 0.807
* **Attrition Recall:** 51%
* **Attrition F1 Score:** 51%

The classification threshold was optimized from **0.50 to 0.30**, increasing attrition recall from 34% to 51%.

## Key Insights
* Attrition was higher among employees working overtime.
* Employees who left had lower average monthly income than employees who stayed.
* Employees who left were younger on average.
* Attrition was associated with shorter tenure at the company.
* Attrition patterns varied across job roles and business travel categories.


## Conclusion
This project demonstrates an end-to-end machine learning workflow for employee attrition prediction, combining predictive modeling with exploratory analysis and business-focused insights.
