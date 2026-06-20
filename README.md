# CodeAlpha - Task 1: Credit Scoring Model

## Project Title
Loan Approval Prediction using Machine Learning

---

## Project Overview
This project focuses on building a machine learning-based credit scoring system to predict loan approval outcomes based on applicant financial and personal information.

Multiple classification models including **Logistic Regression, Decision Tree, and Random Forest** are implemented with complete data preprocessing and exploratory data analysis (EDA).

---

## Problem Statement
The objective is to predict whether a loan application will be approved or rejected based on historical applicant data using supervised learning techniques.

---

## Objectives
- Load and explore dataset
- Perform exploratory data analysis (EDA)
- Handle missing values and inconsistencies
- Encode categorical variables
- Scale numerical features (if required)
- Split dataset into training and testing sets
- Train multiple ML models
- Evaluate and compare model performance

---

## Dataset Information
- **Dataset Source:** https://www.kaggle.com/datasets/sohailaelsayed/loan-prediction  
- **Type:** Structured tabular dataset (CSV)
- **Target Variable:** Loan Status (Approved / Not Approved)
- **Features:** Applicant income, credit history, loan amount, marital status, education, etc.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

---

## Methodology / Workflow

### 1. Data Loading
Dataset is imported using Pandas for inspection and preprocessing.

### 2. Exploratory Data Analysis (EDA)
- Understanding feature distributions
- Checking missing values
- Identifying categorical vs numerical features
- Visualizing correlations (if applied)

### 3. Data Preprocessing
- Handling missing values (mean/mode imputation)
- Encoding categorical variables (Label Encoding / One-Hot Encoding)
- Feature scaling (StandardScaler / MinMaxScaler if required)
- Removing duplicates and irrelevant columns

### 4. Train-Test Split
Dataset is split into:
- Training Set (80%)
- Testing Set (20%)

---

## Machine Learning Models Used
- Logistic Regression (baseline model)
- Decision Tree Classifier
- Random Forest Classifier

---

## Model Evaluation
Models are evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## Results
- Logistic Regression: Baseline performance achieved
- Decision Tree: Improved interpretability
- Random Forest: Best overall accuracy and stability

> Final selected model: Random Forest Classifier (based on performance comparison)

---

## How to Run This Project

### Step 1: Clone Repository
```bash id="clone1"
git clone https://github.com/your-username/codealpha-task1-credit-scoring.git
cd codealpha-task1-credit-scoring
pip install pandas numpy scikit-learn matplotlib seaborn
task1.ipynb
---

### Key Learning Outcomes
- Practical understanding of credit scoring systems
- Importance of data preprocessing in ML pipelines
- Model comparison and performance evaluation techniques
- Hands-on experience with classification algorithms
- End-to-end machine learning workflow implementation
---

## Author
## Sara Sajid
Social Media Marketer | BBA Student | AI & Machine Learning Intern
---

## License
This project is developed for educational and internship purposes only.
---
