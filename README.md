🧠 EEG-Based Epilepsy Detection & Classification using Machine Learning

📌 Project Overview

This project focuses on automated Electroencephalogram (EEG) signal classification using Machine Learning to assist in non-invasive clinical diagnosis of epilepsy. Utilizing the UCI Bangalore Epilepsy EEG Dataset (BEED), the goal is to accurately classify EEG recordings into 4 distinct clinical activity states using a decision tree classification approach.

The model achieves an overall classification accuracy of 83.33% using the CART (Classification and Regression Trees) algorithm.

🎯 Key Objectives

Process multi-feature EEG tabular signal data using robust data preprocessing techniques.

Scale and normalize numeric continuous feature vectors for optimal model execution.

Implement and train a CART Decision Tree model using Gini Impurity.

Evaluate model performance using multi-class metrics (Precision, Recall, F1-Score, and Confusion Matrix).

Visualize decision rules and tree branching up to top structural levels.

🛠️ Tech Stack & Tools

Environment: Google Colab / Jupyter Notebook

Language: Python 3.x

Data Manipulation: pandas, numpy

Data Preprocessing & ML: scikit-learn

StandardScaler (Feature Normalization)

LabelEncoder (Target Categorical Encoding)

train_test_split (Data Partitioning)

DecisionTreeClassifier (CART Model Execution)

Visualization: matplotlib

📊 Dataset Architecture

Dataset Name: Bangalore Epilepsy EEG Dataset (BEED)

File Format: .xlsx (Excel Spreadsheet)

Total Records: 5,600 samples

Features: 16 continuous numerical feature columns (X1 to X16)

Target Variable: y (Multi-class target with 4 distinct states: 0, 1, 2, 3)

Train-Test Split: 70% Training (3,920 samples) | 30% Testing (1,680 samples)

🚀 Machine Learning Pipeline Workflow

[ BEED Excel Dataset ] 

 Data - Preprocessing - Algorithm - Results
