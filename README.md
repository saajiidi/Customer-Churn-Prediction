# Telecom Customer Churn Prediction

## Overview
This project predicts customer churn for a telecom company using machine learning. The goal is to identify customers at risk of leaving and provide actionable recommendations to retain them.

## Dataset
The dataset used is the [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn) from Kaggle.

## Methodology
1. **Data Cleaning**: Handled missing values and encoded categorical variables.
2. **EDA**: Analyzed churn rates and correlations.
3. **Modeling**: Built and evaluated models using Logistic Regression, Random Forest, and XGBoost.
4. **Insights**: Identified key drivers of churn and provided recommendations.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/telecom-churn-prediction.git

2.  Install dependencies:

   ```bash
   pip install -r requirements.txt

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/churn_prediction.ipynb

## Results
The XGBoost model achieved an ROC-AUC score of 0.85.

Key drivers of churn include contract type, tenure, and monthly charges.

## Author
Sajid Islam