# 📉 Customer Churn Prediction using Machine Learning

An end-to-end **supervised machine learning project** that predicts whether a customer is likely to **churn (leave a company)** based on behavioral, demographic, and service usage features. This project demonstrates real-world **binary classification**, feature engineering, model comparison, and business-focused interpretation.

---

## Problem Statement

Customer churn is one of the biggest challenges for subscription-based businesses (telecom, banking, SaaS, e-commerce). The goal of this project is to:

- Predict **which customers are likely to churn**
- Help companies **reduce revenue loss**
- Support **data-driven retention strategies**

---

## Dataset Description

- Dataset Type: Customer subscription data  
- Target Variable: `Churn` (Yes = 1, No = 0)
- Common Features:
  - Customer demographics
  - Contract type
  - Monthly charges
  - Internet & phone services
  - Payment method
  - Tenure

>  Dataset is **not uploaded to GitHub** for privacy and size reasons.  
> You can use a public version from Kaggle such as:

🔗 https://www.kaggle.com/blastchar/telco-customer-churn

---

## Tech Stack

- **Programming Language:** Python  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  
- **Models Used:**  
  - Logistic Regression  
  - Random Forest Classifier  
- **Environment:** Google Colab / Jupyter Notebook  

---

## Project Workflow

1. **Data Loading**
2. **Data Cleaning & Preprocessing**
   - Missing value handling
   - Categorical encoding
   - Feature scaling
3. **Exploratory Data Analysis (EDA)**
4. **Train–Test Split**
5. **Model Training**
   - Logistic Regression
   - Random Forest
6. **Model Evaluation**
7. **Customer Churn Prediction Function**

---

##  Machine Learning Models

###  Logistic Regression  
Used for:
- Interpretability  
- Understanding feature impact on churn  

###  Random Forest Classifier  
Used for:
- Higher predictive performance  
- Capturing nonlinear relationships  

---

## 📈 Model Evaluation Metrics

| Metric | Description |
|--------|-------------|
| Accuracy | Overall performance |
| Precision | Correct churn predictions |
| Recall | Ability to detect actual churn |
| F1-Score | Balance between precision & recall |
| Confusion Matrix | Error analysis |

---

## 🧮 Example Prediction Output

