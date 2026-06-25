# CodeAlpha_Credit_Scoring_Model
A Machine Learning model using Random Forest to predict creditworthiness with 78.53% accuracy.
# Credit Scoring Model - CodeAlpha Task 1

This repository contains a Machine Learning project developed during my internship at CodeAlpha. The objective is to predict individual creditworthiness (Poor, Standard, Good) based on historical financial data.

## 📊 Performance Summary
- **Model Used:** Random Forest Classifier (100 Trees)
- **Overall Accuracy:** 78.53%
- **Data Size:** 100,000 Customer Records
- **Key Features Analyzed:** Annual Income, Outstanding Debt, Payment Delays, Number of Bank Accounts/Cards.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Management:** Pandas, NumPy
- **Machine Learning Engine:** Scikit-Learn (StandardScaler, train_test_split, RandomForestClassifier)
- **Evaluation:** Confusion Matrix, Classification Report

## 📋 Evaluation Insights
- **Class 0 (Poor/Risky):** Achieved a **Recall of 0.81**, meaning the model successfully caught 81% of high-risk customers, preventing potential bad loans for banks.
- **Confusion Matrix:** Out of 20,000 test cases, only **11 high-risk cases** were misclassified as 'Good', demonstrating high reliability.
