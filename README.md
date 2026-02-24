#  Machine Learning Projects Portfolio

##  Overview
This repository contains two end-to-end Machine Learning projects developed as part of an AI/ML internship.  
Each project follows the complete machine learning workflow including data preprocessing, exploratory data analysis (EDA), model building, evaluation, and comparison.

Projects Included:
-  House Price Prediction (Regression)
-  Loan Approval Prediction (Classification)

---

#  Project 1: House Price Prediction

##  Problem Statement
To develop a supervised regression model that predicts the median value of houses (MEDV) based on housing-related features.

**Problem Type:** Regression  
**Target Variable:** MEDV  

---

##  Dataset Description
The dataset consists of 13 independent variables and 1 target variable.

Important Features:
- CRIM – Crime rate
- RM – Average number of rooms
- LSTAT – Percentage of lower income population
- PTRATIO – Pupil-teacher ratio
- TAX – Property tax rate
- NOX – Nitric oxide concentration

---

##  Methodology

### 1️ Data Preprocessing
- Handling missing values
- Train-Test Split (80% training, 20% testing)
- Feature scaling using StandardScaler

### 2️ Exploratory Data Analysis
- Correlation heatmap
- Feature relationship analysis

### 3️ Models Implemented
- Linear Regression
- Random Forest Regressor

---

##  Model Performance

Linear Regression:
- Training R² Score: 0.74
- Testing R² Score: 0.67

Random Forest Regressor:
- Training R² Score: 0.97
- Testing R² Score: 0.85

Best Performing Model: Random Forest Regressor

---

##  Key Insights
- RM shows strong positive correlation with house price.
- LSTAT shows strong negative correlation.
- Ensemble models capture nonlinear patterns effectively.

---

#  Project 2: Loan Approval Prediction

## Problem Statement
To develop a classification model that predicts whether a loan application will be approved or rejected.

**Problem Type:** Classification  
**Target Variable:** Loan_Status  

---

##  Dataset Description

Features include:
- Gender
- Married
- Dependents
- Education
- ApplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

Loan_ID was removed as it does not contribute to prediction.

---

##  Methodology

### 1️ Data Preprocessing
- Missing value imputation
- Encoding categorical variables
- Feature scaling
- Stratified train-test split (80/20)

### 2️ Models Implemented
- Logistic Regression
- Support Vector Machine (Linear Kernel)
- Random Forest Classifier

---

##  Model Accuracy

- Logistic Regression: 82.11%
- Support Vector Machine: 82.11%
- Random Forest: 81.30%

Final Selected Model: Logistic Regression

---

##  Key Insights
- Credit_History is the strongest predictor of loan approval.
- Dataset is nearly linearly separable.
- Complex models did not significantly improve performance.

---

#  Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

#  Repository Structure

```
project 1.ipynb
project2.ipynb
HousingData.csv
loan_prediction.csv
REPORT ANALYSIS.pdf
README.md
```

---

#  How to Run

1. Clone the repository  
2. Install required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open Jupyter Notebook  
4. Run the notebooks step by step  

---

#  Future Improvements
- Hyperparameter tuning using GridSearchCV
- Cross-validation
- SMOTE for handling class imbalance
- Model deployment using Flask or Streamlit
- Real-time prediction system

---

#  Author
S. Shivani  
AI/ML Intern  
PKIET – February 2026