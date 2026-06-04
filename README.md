CREDIT CARD FRAUD DETECTION – EXPLORATORY DATA ANALYSIS
Introduction

Credit card fraud is one of the major challenges in the financial sector, leading to significant financial losses every year. With the increasing number of online transactions, detecting fraudulent activities has become crucial for banks and financial institutions.

This project focuses on analyzing a credit card transaction dataset using Python. By applying Exploratory Data Analysis (EDA) and visualization techniques, we aim to understand transaction patterns, detect anomalies, and identify characteristics of fraudulent transactions.

Using libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly, the dataset is explored and visualized to extract meaningful insights that help in understanding fraud behavior.

Problem Statement

Credit card transactions generate large volumes of data every second. While most transactions are normal, a very small percentage are fraudulent. These fraud cases are often hidden within large datasets and are difficult to detect manually.

There is a need to analyze transaction data to understand patterns such as transaction amount distribution, class imbalance, and relationships between variables. By performing EDA and visualization, we can gain insights into how fraudulent transactions differ from normal ones and support future fraud detection systems.

Objectives
To load and explore the credit card transaction dataset
To clean the dataset by removing duplicates and handling missing values
To perform statistical analysis of transactions
To analyze the distribution of fraudulent and normal transactions
To study transaction amount patterns
To identify relationships using correlation analysis
To create a risk level classification based on transaction amount
To visualize data using Seaborn and Plotly charts
To generate insights about fraud behavior patterns
Tools and Technologies Used

Programming Language: Python

Libraries Used:

Pandas – Data manipulation and analysis
NumPy – Numerical computations
Matplotlib – Basic visualization
Seaborn – Statistical visualization
Plotly Express – Interactive dashboards

Dataset: Credit Card Transaction Dataset (CSV format)

Methodology
Step 1: Data Collection

The dataset is loaded from a CSV file containing credit card transactions with features such as Time, Amount, and Class (Fraud/Normal).

Step 2: Data Cleaning
Checking missing values
Removing duplicate records
Ensuring data consistency
Step 3: Exploratory Data Analysis (EDA)

Basic statistical analysis is performed to understand:

Transaction distribution
Fraud vs normal transaction count
Summary statistics of dataset
Step 4: Data Visualization

Different visualization techniques are used:

Count Plot → Fraud vs Normal transactions
Histogram → Transaction amount distribution
Box Plot → Fraud vs amount comparison
Heatmap → Correlation between variables
Step 5: Risk Analysis

A risk level is created based on transaction amount:

Low Risk: Amount < 50
Medium Risk: 50 ≤ Amount < 200
High Risk: Amount ≥ 200
Step 6: Model Building (Linear Regression)

A simple Linear Regression model is applied using:

Features: Time, Amount
Target: Class (Fraud/Normal)
Step 7: Model Evaluation

The model is evaluated using:

R² Score
Mean Squared Error (MSE)
Step 8: Insights Generation

Key insights include:

Number of fraud vs normal transactions
Fraud percentage in dataset
Transaction patterns based on amount
Step 9: Interactive Visualization (Plotly)

Interactive dashboards are created using Plotly:

Fraud distribution
Time vs Amount scatter plot
Risk level distribution
Correlation heatmap
Expected Output

The project produces visual insights such as:

Fraud vs normal transaction distribution
Transaction amount behavior patterns
Correlation between features
Risk classification of transactions
Interactive charts for better understanding
Applications
Banking fraud detection systems
Financial transaction monitoring
Risk analysis in payment systems
Data science learning projects
Security analytics
Conclusion

This project demonstrates how Python can be used to analyze and visualize financial transaction data effectively. Through Exploratory Data Analysis and visualization techniques, we can understand fraud patterns and transaction behavior. These insights help in building better fraud detection systems and improving financial security.
<img width="776" height="589" alt="image" src="https://github.com/user-attachments/assets/751eb454-86a9-47b8-83ff-395fa9d19576" />
<img width="793" height="590" alt="image" src="https://github.com/user-attachments/assets/f555d7d0-b340-40da-bc9c-a0ad62e06602" />
