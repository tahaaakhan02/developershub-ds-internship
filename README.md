# — Data Science & Analytics

This repository contains all 5 completed tasks for the **DevelopersHub Corporation Data Science & Analytics Internship Program**.

---

## Tasks Overview

### Task 1: Exploring and Visualizing the Iris Dataset
**Objective:** Understand how to read, summarize, and visualize a dataset.  
**Dataset:** Iris Dataset (loaded via seaborn)  
**Approach:** Loaded and inspected the dataset, handled duplicates, and created scatter plots, histograms, box plots, and a pairplot to analyze feature distributions and inter-species relationships.  
**Key Insight:** Petal features (length & width) are the strongest discriminators between species. *Iris setosa* is clearly separable from the other two species.

---

### Task 2: Credit Risk Prediction
**Objective:** Predict whether a loan applicant is likely to default.  
**Dataset:** [Loan Prediction Dataset — Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)  
**Approach:** Handled missing values via mode/median imputation, encoded categorical features, trained Logistic Regression and Decision Tree classifiers, evaluated using accuracy and confusion matrix.  
**Key Insight:** Credit history is the most influential feature. Applicants with good credit history have significantly higher loan approval rates.

---

### Task 3: Customer Churn Prediction (Bank Customers)
**Objective:** Identify customers likely to leave the bank.  
**Dataset:** [Churn Modelling Dataset — Kaggle](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling)  
**Approach:** Cleaned data, applied Label Encoding for gender and One-Hot Encoding for geography, trained Logistic Regression and Random Forest models, analyzed feature importance.  
**Key Insight:** Age is the top predictor of churn. Older, single-product, inactive female customers are most at risk of churning.

---

### Task 4: Predicting Insurance Claim Amounts
**Objective:** Estimate medical insurance charges based on personal data.  
**Dataset:** [Medical Cost Personal Dataset — Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
**Approach:** Trained a Linear Regression model, visualized the impact of BMI, age, and smoking status on charges, evaluated using MAE, RMSE, and R².  
**Key Insight:** Smoking status is the dominant factor — smokers pay 3-4x more than non-smokers. Age and BMI also have strong positive correlations with charges.

---

### Task 5: Personal Loan Acceptance Prediction
**Objective:** Predict which customers are likely to accept a personal loan offer.  
**Dataset:** [Bank Personal Loan Modelling — Kaggle](https://www.kaggle.com/datasets/teertha/personal-loan-modeling)  
**Approach:** Explored features (age, income, education, CC spending), trained Logistic Regression and Decision Tree models, analyzed feature importance and customer profiles.  
**Key Insight:** Income and CC average spending are top predictors. High-income, high-spending, graduate-educated customers should be the primary target for loan marketing campaigns.

---

## Repository Structure

```
developershub-ds-internship/
│
├── task1_iris_eda.ipynb
├── task2_credit_risk.ipynb
├── task3_churn_prediction.ipynb
├── task4_insurance_prediction.ipynb
├── task5_loan_acceptance.ipynb
└── README.md
```

---

## Tech Stack

- **Python 3.10**
- **pandas**, **numpy** — data manipulation
- **matplotlib**, **seaborn** — visualization
- **scikit-learn** — machine learning models and evaluation

---

## How to Run

1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Download the required datasets from the Kaggle links above and place them in the same directory as the notebooks
4. Open any notebook with Jupyter and run all cells
