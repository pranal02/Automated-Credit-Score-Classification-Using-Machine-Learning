# Automated-Credit-Score-Classification-Using-Machine-Learning
# Project Overview
- This project aims to build an intelligent system that classifies individuals into credit score brackets based on their credit-related information. By automating the credit scoring process, the system reduces manual efforts and provides a scalable solution for credit risk assessment. We utilize three different machine learning models—Decision Tree, Random Forest, and Support Vector Machine (SVM)—and perform hyperparameter tuning to find the best model for classification.

# Dataset
- The dataset contains detailed information about individuals, including their credit history and financial status. The primary target variable is Credit_Score, which categorizes the creditworthiness of individuals.

# Dataset Columns:
- ID: Unique identification of an entry.
- Customer_ID: Unique identification of a person.
- Month: Month of the year.
- Name: Name of a person.
- Age: Age of the person.
- SSN: Social Security Number of a person.
- Occupation: Occupation of the person.
- Annual_Income: Annual income of the person.
- Monthly_Inhand_Salary: Monthly base salary of a person.
- Num_Bank_Accounts: Number of bank accounts a person holds.
- Num_Credit_Card: Number of other credit cards held by a person.
- Interest_Rate: Interest rate on credit card.
- Num_of_Loan: Number of loans taken from the bank.
- Type_of_Loan: Types of loan taken by a person.
- Delay_from_due_date: Average number of days delayed from the payment date.
- Num_of_Delayed_Payment: Number of delayed payments.
- Changed_Credit_Limit: Percentage change in credit card limit.
- Num_Credit_Inquiries: Number of credit card inquiries.
- Credit_Mix: Classification of the mix of credits.
- Outstanding_Debt: Remaining debt to be paid (in USD).
- Credit_Utilization_Ratio: Utilization ratio of credit card.
- Credit_History_Age: The age of credit history of the person.
- Payment_of_Min_Amount: Whether the minimum amount was paid.
- Total_EMI_per_month: Monthly EMI payments (in USD).
- Amount_Invested_monthly: Monthly amount invested by the customer (in USD).
- Payment_Behaviour: Payment behavior of the customer.
- Monthly_Balance: Monthly balance amount of the customer (in USD).
- Credit_Score: The target variable representing the credit score bracket.
# Project Workflow
- Data Preparation

- Load and understand the dataset.
- Handle missing values using imputation techniques.
- Encode categorical features using Label Encoding.
- Scale numerical features to standardize the data.
- Split the data into training and testing sets.
# Model Building

# Implement three different machine learning models:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Perform hyperparameter tuning using Grid Search to optimize each model.
# Model Evaluation

- Evaluate each model using metrics such as accuracy, precision, recall, and F1 score.
- Compare the performance of all three models to select the best one.
# Model Selection

- Select the best model based on performance metrics.
- Analyze feature importance and visualize decision boundaries (where applicable).
