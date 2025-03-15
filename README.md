Customer Churn Analysis - Telecom Company "Neo"

Project Overview

This project aims to analyze customer churn for the telecom company Neo. The company is facing a high churn rate, where customers are switching to competitors. The objective is to explore and manipulate customer data, extract meaningful insights, and visualize trends to understand the factors influencing churn.

Dataset Information

The dataset used for this project is customer_churn, which contains various customer details such as tenure, payment methods, contract type, and whether the customer has churned or not.

Data Dictionary

CustomerID: Unique ID for each customer

Gender: Male or Female

SeniorCitizen: Whether the customer is a senior citizen (1) or not (0)

Partner: Whether the customer has a partner (Yes/No)

Dependents: Whether the customer has dependents (Yes/No)

Tenure: Number of months the customer has stayed with the company

PhoneService: Whether the customer has phone service (Yes/No)

MultipleLines: Whether the customer has multiple lines (Yes/No)

InternetService: Type of internet service (DSL, Fiber optic, No)

OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies: Various internet service features (Yes/No/No internet service)

Contract: Customer’s contract type (Month-to-month, One year, Two year)

PaperlessBilling: Whether the customer has paperless billing (Yes/No)

PaymentMethod: Customer’s payment method (Electronic check, Mailed check, Bank transfer, Credit card)

MonthlyCharges: Monthly amount charged to the customer

TotalCharges: Total amount charged to the customer

Churn: Whether the customer has churned (Yes/No)

Tasks Performed

A) Data Manipulation

Extract specific columns:

Extract the 5th column and store it in customer_5

Extract the 15th column and store it in customer_15

Filter specific customer groups:

Extract all male senior citizens who use Electronic Check as their payment method and store the result in senior_male_electronic

Extract all customers whose tenure is greater than 70 months OR whose monthly charges exceed $100, and store the result in customer_total_tenure

B) Data Visualization

Bar Plot for Internet Service Distribution:

Set x-axis label to 'Categories of Internet Service'

Set y-axis label to 'Count of Categories'

Set title as 'Distribution of Internet Service'

Installation and Setup

Prerequisites

Ensure the following dependencies are installed:

Python (3.x)

Jupyter Notebook or any Python IDE

Pandas (for data manipulation)

Matplotlib & Seaborn (for data visualization)

Steps to Run the Project

Clone the Repository

git clone https://github.com/your-repo/customer-churn-analysis.git
cd customer-churn-analysis

Set Up a Virtual Environment (Optional)

python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

Install Required Packages

pip install pandas matplotlib seaborn

Run the Jupyter Notebook

jupyter notebook

Open the .ipynb file and execute the cells.



