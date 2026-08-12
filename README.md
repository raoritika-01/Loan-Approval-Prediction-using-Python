# Loan Approval Prediction

This project predicts whether a loan application will be approved or rejected using Machine Learning. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction for new applicants.

---

## Project Overview

The objective of this project is to build a classification model that predicts loan approval based on applicant information such as income, CIBIL score, loan amount, education, employment status, and asset values.

The project follows a complete machine learning workflow, from data cleaning to model evaluation and prediction.

---

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Categorical feature encoding
- Correlation analysis
- Model training and comparison
- Feature importance analysis
- Loan approval prediction for new applicants

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

### 1. Data Preprocessing

- Loaded the loan approval dataset
- Removed unnecessary columns
- Cleaned categorical values
- Handled invalid data
- Encoded categorical variables

### 2. Exploratory Data Analysis

- Loan approval distribution
- CIBIL score analysis
- Correlation heatmap
- Feature relationship analysis

### 3. Model Building

The following machine learning models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 4. Model Evaluation

Models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

### 5. Feature Importance

Random Forest feature importance was used to identify the most influential features affecting loan approval.

### 6. Prediction

The trained Random Forest model predicts whether a new loan applicant is likely to be approved or rejected based on the provided details.

---

## Visualizations

- Loan Approval Distribution
- CIBIL Score vs Loan Status
- Correlation Heatmap
- Confusion Matrix
- Feature Importance Chart

---

## Project Structure

```text
├── data/
│   └── loan_approval_dataset.csv
│
├── notebooks/
│   └── Loan_Approval_Prediction.ipynb
│
├── images/
│   ├── loan_distribution.png
│   ├── cibil_score_boxplot.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
├── README.md
└── requirements.txt
```

---

## Installation

```bash
git clone https://github.com/yourusername/Loan-Approval-Prediction.git

cd Loan-Approval-Prediction

pip install -r requirements.txt
```

---

## Run the Project

```bash
jupyter notebook
```

Open:

```text
Loan_Approval_Prediction.ipynb
```

---

## Libraries Used

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## Future Improvements

- Hyperparameter tuning for improved model performance
- Cross-validation for robust evaluation
- Deployment using Streamlit or Flask
- Integration with a web-based loan approval system
- Testing additional ensemble learning models

---

## Author

**Ritika Yadav**

If you found this project useful, consider giving it a star on GitHub.
