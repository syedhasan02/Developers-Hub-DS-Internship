Project Overview: Credit Risk Prediction
The objective of this task is to predict whether a loan applicant is likely to default on a loan . This is a binary classification problem where the goal is to build a model that can accurately identify high-risk applicants based on historical data.

Dataset Description
The Loan Prediction Dataset (from Kaggle) was used for this analysis. It contains various features such as:
* Demographics: Gender, Marital Status, Dependents, and Education.
* Financials: Applicant Income, Co-applicant Income, and Loan Amount.
* Credit History: Past credit records which are crucial for determining risk.

My Approach
1) Data Cleaning: Handled missing values using mode (categorical) and median (numerical) imputation. Processed the Dependents column and addressed the "3+" entry for numeric compatibility.
2) Exploratory Data Analysis (EDA): Performed visual analysis using Seaborn and Matplotlib to identify trends in Loan Amount, Education, and Applicant Income.
3) Preprocessing: Converted categorical variables into numerical format using One-Hot Encoding to prepare the data for machine learning.
4) Modeling & Evaluation: Trained a Logistic Regression classifier with an 80/20 train-test split. Evaluated performance using Accuracy (79%) and a Confusion Matrix.

Results & Insights
Model Performance: The Logistic Regression model achieved a final accuracy score of ~79%.
Key Findings: Credit History was the strongest indicator of loan acceptance. Applicants with a positive credit history were significantly more likely to be approved.
Evaluation: The Confusion Matrix confirmed that the model is particularly effective at identifying applicants who are likely to pay back their loans.
