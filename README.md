# Telco Customer Churn Analysis

An end-to-end data analysis and machine learning project aimed at predicting customer churn using the Telco Customer Churn dataset. This project identifies key indicators of customer churn and builds predictive models to help businesses improve retention strategies.

---

## 📌 Project Overview
Customer churn occurs when customers stop doing business with a company. In the telecom industry, retaining existing customers is often much more cost-effective than acquiring new ones. This project analyzes customer behavior, demographics, and account information to predict who is likely to churn.

## 📊 Dataset
The dataset used in this project is the well-known **WA_Fn-UseC_-Telco-Customer-Churn.csv**, which includes information about:
* **Demographics:** Gender, seniority, partners, and dependents.
* **Customer Account Info:** Tenure, contract type, payment method, paperless billing, monthly charges, and total charges.
* **Services:** Phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV/movies.
* **Target Variable:** `Churn` (Whether the customer left within the last month or not).

## 🚀 Features & Workflow
1.  **Data Cleaning & Preprocessing:** Handling missing values (e.g., blank spaces in `TotalCharges`), encoding categorical variables, and feature scaling.
2.  **Exploratory Data Analysis (EDA):** Visualizing churn rates against different features like tenure, contract type, and monthly charges to uncover patterns.
3.  **Feature Engineering:** Selecting and transforming key variables to optimize model performance.
4.  **Model Building:** Training multiple machine learning algorithms (e.g., Logistic Regression, Random Forest, or XGBoost).
5.  **Evaluation:** Assessing performance using metrics such as Accuracy, Precision, Recall, and F1-Score.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Environment:** Jupyter Notebook

## 📁 Repository Structure
```text
├── WA_Fn-UseC_-Telco-Customer-Churn.csv       # Raw Dataset
├── WA_Fn_UseC__Telco_Customer_Churn.ipynb     # Jupyter Notebook with full analysis
└── README.md                                  # Project Documentation
