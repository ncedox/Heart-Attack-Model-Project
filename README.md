# Hospital Readmission Prediction Project

## Overview

This project uses machine learning to predict whether a heart failure patient will be readmitted to the hospital within 30 days after discharge.

Hospital readmissions are a major challenge in healthcare because they increase costs and can negatively affect patient health. By identifying high-risk patients early, hospitals can provide additional support and reduce avoidable readmissions.

---

## Problem Statement

Can machine learning predict which heart failure patients are most likely to be readmitted within 30 days?

The goal is to help healthcare providers identify high-risk patients and improve patient care.

---

## Dataset

The dataset contains 3,000 patient records and includes:

### Clinical Information

* Age
* Gender
* BMI
* BNP
* Sodium
* Creatinine
* Blood Pressure
* Heart Rate

### Treatment Information

* ACE Inhibitor
* Beta Blocker
* Diuretic

### Social Factors

* Medication Adherence Score
* Income Level
* Distance to Hospital

### Target Variable

* Readmitted within 30 days (Yes/No)

---

## Project Steps

### 1. Data Cleaning

* Checked for missing values
* Filled missing data using median values

### 2. Data Preparation

* Encoded categorical variables
* Split data into training and testing sets
* Scaled features where needed

### 3. Handle Class Imbalance

* Used SMOTE to balance the dataset
* Improved the model's ability to identify readmitted patients

### 4. Model Building

The following machine learning models were trained and tested:

* Logistic Regression
* Random Forest
* XGBoost
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes

### 5. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 61.6%    |
| Random Forest       | 64.3%    |
| XGBoost             | 61.5%    |
| KNN                 | 62.3%    |
| Naive Bayes         | 65.0%    |
| SVM                 | 66.0%    |

### Best Model

Support Vector Machine (SVM) achieved the best overall performance with an accuracy of 66%.

### Important Finding

Naive Bayes achieved the highest recall, meaning it was the best model at identifying patients who were likely to be readmitted.

In healthcare, recall is very important because missing a high-risk patient can have serious consequences.

---

## Tools Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Imbalanced-Learn (SMOTE)
* Jupyter Notebook

---

## Key Learnings

Through this project I learned how to:

* Clean and prepare healthcare data
* Handle missing values
* Apply SMOTE for imbalanced data
* Train and compare multiple machine learning models
* Evaluate model performance using healthcare-focused metrics
* Interpret results and make data-driven recommendations

---

## Future Improvements

* Hyperparameter tuning
* Feature importance analysis
* SHAP explainability
* Neural Networks
* Model deployment with Streamlit

---

## Author

**Thabo Mailula**


