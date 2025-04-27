# Predicting Severe Chronic Kidney Disease (CKD) Events Using Electronic Health Records (EHRs)

![GitHub Repo Size](https://img.shields.io/github/repo-size/shubh9mehta/ckd-events-prediction)
![GitHub License](https://img.shields.io/github/license/shubh9mehta/ckd-events-prediction)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

---

## 📖 Project Overview

This project aims to predict the risk of **severe Chronic Kidney Disease (CKD) events** using patient Electronic Health Records (EHRs) from Abu Dhabi.  
By leveraging clinical features like **eGFR**, **Creatinine**, **Age**, **Diabetes History**, and more, we built predictive machine learning models to help enable early intervention for at-risk patients.

> This project covers **real-world healthcare EHR analysis**, **data cleaning**, **feature engineering**, **statistical testing**, **model building**, and **interpretability** using SHAP.

---

## 🛠️ Tools & Technologies Used

- Python 3.8+
- Jupyter Notebooks
- Pandas, NumPy
- scikit-learn
- XGBoost
- SHAP (Explainable AI)
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- Git & GitHub

---

## 📢 Acknowledgements

- **Dataset Source:** [Chronic Kidney Disease EHRs - Abu Dhabi (Kaggle)](https://www.kaggle.com/datasets/davidechicco/chronic-kidney-disease-ehrs-abu-dhabi?resource=download)
- Dataset collected and made public by Davide Chicco on Kaggle.
- Inspired by real-world clinical predictive modeling research.

## 📂 Project Structure

```plaintext
ckd-events-prediction/
├── data/
│   ├── raw/                 # Original raw data files
│   ├── processed/            # Cleaned and feature-engineered datasets
├── models/
│   ├── (saved models - .pkl) # Logistic Regression, XGBoost, Voting Classifier
├── Notebooks/
│   ├── Phase 1: Data Cleaning
│   ├── Phase 2: Statistical Testing
│   ├── Phase 3: Feature Engineering
│   ├── Phase 4-5-6: Modeling, Evaluation, SHAP Analysis
├── requirements.txt
├── README.md
├── .gitignore




