🚗 Vehicle Insurance Fraud Detection
📌 Project Overview

Insurance fraud causes significant financial losses every year.
This project focuses on analyzing vehicle insurance claim data to understand patterns related to fraudulent and non-fraudulent claims using data analysis and visualization techniques.

The goal is to:
Explore the dataset
Understand relationships between features and fraud
Identify important patterns that help in fraud detection
Improve model understanding through visualization

📂 Dataset

File name: Vehicle_fraud_Insurance_.csv
Domain: Insurance / Fraud Detection
Target Variable: FraudFound_P
0 → Non-Fraud
1 → Fraud

🛠️ Technologies Used

Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook

🔄 Project Workflow

Data Loading
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Fraud vs Feature Relationship Analysis
Model Evaluation (Confusion Matrix Analysis)

🧹 Data Preprocessing Methods

Handling missing values
Encoding categorical variables
Feature selection
Handling class imbalance
Data type conversion
Outlier analysis

📊 Exploratory Data Analysis & Visualizations
🔹 Categorical Features vs Fraud

Fraud vs Accident Area
Fraud vs Vehicle Price
Fraud vs Policy Type
Fraud vs Agent Type

📈 Visualizations used:

Bar plots
Count plots
Pie charts

🔹 Numerical Features vs Fraud

Deductible vs Fraud
Driver Rating vs Fraud
Age vs Fraud

📉 Visualizations used:

Box plots
Violin plots
Histogram split by fraud
These plots help in understanding how numerical values behave differently for fraud and non-fraud cases.

📈 Model Performance Analysis

The model performance was evaluated using:
Confusion Matrix
True Positives (TP)
True Negatives (TN)
False Positives (FP)
False Negatives (FN)

⚠️ Observations

TP and TN values are comparatively low
FP and FN values are high
Class imbalance impacts fraud prediction

🔧 Improvement Plan

Handle class imbalance using resampling techniques (SMOTE / class weights)
Perform better feature engineering
Tune model hyperparameters
Focus on Recall and F1-Score instead of accuracy

🎯 Key Insights

Fraud cases are highly imbalanced
Certain categorical features show strong correlation with fraud
Visualization helps identify fraud-prone patterns
Reducing False Negatives is critical in fraud detection

📁 Project Files

Vehicle_fraud_Insurance.ipynb → Main notebook
Vehicle_fraud_Insurance_.csv → Dataset
README.md → Project documentation
