# Telecom Customer Churn Analysis & Predictions

This notebook project explores customer churn in a telecommunications company. This is done by using
Explatory Data Analysis (EDA) and calculations to find which attributes of a customer are most linked
to churning (leaving) or not.

## Project Overview

- Used EDA to explore key factors influencing churn rates in the company
- Performed data preprocessing (handling null data, encoding categorical variables, scaling)
- Implemented and fitted 3 classification models:
    - Logistic Regression
    - K-Nearest Neighbours
    - Decision Tree Classifier

## Key Insights from EDA

Tenure, the monthly amount charged, the contract type (of a customer), and whether they streamed
TV/movies were strongly linked to churn.
The customers with shorter tenures, higher monthly charges, and month-to-month contracts were much
more likely to churn.
When performing EDA, key proposals were made for the company to reduce customers who were leaving, these
included regular customer feedback, discounts/special offers, family bundles, and loyalty incentives.

## Model Performance

The Decision Tree Classifier performed the best among the models used, showing the most consistency between precision and recall.
Logistic Regression and KNN underperformed in these metrics relative to the Decision Tree Classifier.
However, even the best model fell short of initial expectations, leaving room for future improvement.

## Next Steps (future improvement)

- Hyperparameter tuning to optimise model performance.
- Overlooking the feature engineering, seeing if any variables could be harming the performance.
- Testing alternative models, such as Random Forest, Gradient Boosting, or XGBoost.

## Tech Stack

- Python 3
- pandas, NumPy - data wrangling
- matplotlib, seaborn - data visualisation
- scikit-learn - preprocessing, model building/fitting, and evaluation.
