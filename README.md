# E-COMMERCE-CUSTOMER-CHURN-ANALYSIS
# E-commerce Customer Churn Analysis Using MySQL

## 📌 Project Overview

This project analyzes e-commerce customer data using MySQL to understand customer churn, purchasing behavior, satisfaction levels, payment preferences, and customer complaints. SQL queries are used to clean and transform the dataset, analyze customer trends, and extract meaningful insights that can help businesses improve customer retention.

## 🎯 Project Objectives

- Analyze customer churn and active customer patterns.
- Clean missing values and standardize inconsistent data.
- Explore customer purchasing behavior and order categories.
- Analyze payment methods and coupon usage.
- Evaluate customer satisfaction and complaints.
- Examine cashback amounts and customer tenure.
- Identify patterns that may help improve customer retention.

## 🛠️ Tools and Technologies

- MySQL
- MySQL Workbench
- SQL (Structured Query Language)
- Data Cleaning and Transformation
- Aggregate Functions
- Subqueries
- CASE Statements
- JOIN Operations
- GROUP BY and ORDER BY

## 📂 Dataset Description

The project uses an e-commerce customer dataset containing information about:

- **Customer Details:** Customer ID, gender, marital status, and city tier.
- **Customer Engagement:** Tenure, hours spent on the app, and registered devices.
- **Purchasing Behavior:** Preferred order category, order count, and coupon usage.
- **Payment Information:** Preferred payment method and cashback amount.
- **Customer Experience:** Satisfaction score and complaint status.
- **Delivery Information:** Warehouse-to-home distance and days since the last order.
- **Churn Information:** Customer churn status.

## 🔄 Project Workflow

### 1. Database and Table Creation
- Create the `ecomm` database.
- Create the customer table with appropriate data types and constraints.
- Import customer records into the database.

### 2. Data Cleaning
- Handle missing values in selected numerical columns.
- Identify and remove records with unusually large warehouse-to-home distances according to the chosen cleaning rule.
- Standardize inconsistent values in device, payment, and order category columns.
- Rename columns for better readability.

### 3. Data Transformation
- Create a `ComplaintReceived` column with Yes/No values.
- Create a `ChurnStatus` column to classify customers as Churned or Active.
- Remove the original binary churn and complaint columns after creating the readable categories.

### 4. Exploratory Data Analysis
Use SQL queries to investigate:
- Active and churned customer counts.
- Average tenure and total cashback for churned customers.
- Complaint percentage among churned customers.
- Customer distribution by city tier.
- Preferred payment methods among active customers.
- Coupon usage by gender.
- Satisfaction scores and order categories.

### 5. Advanced SQL Analysis
- Use subqueries to compare customer orders with average order counts.
- Apply `CASE` statements to categorize delivery distances.
- Use aggregate functions to calculate totals, averages, and counts.
- Group results by churn status and customer characteristics.
- Join customer and returns tables to examine records associated with churned customers who submitted complaints.

## 📊 Key Business Questions

1. How many customers are active, and how many have churned?
2. What are the average tenure and total cashback amounts of churned customers?
3. What percentage of churned customers have submitted complaints?
4. Which city tier has the most churned customers purchasing laptops and accessories?
5. Which payment method is most popular among active customers?
6. Which gender uses the most coupons?
7. How do satisfaction scores vary among customers who complain?
8. Which product categories have the highest average cashback?
9. How are delivery distances associated with customer churn?
10. Which churned customers have also submitted complaints?

## 💡 Skills Demonstrated

- Database creation and table management
- SQL data cleaning and standardization
- Handling missing values
- Data transformation using `UPDATE` and `CASE`
- Aggregate functions such as `COUNT()`, `SUM()`, and `AVG()`
- Data grouping and filtering
- Subqueries
- Table joins
- Business-focused data analysis
- Extracting actionable insights from structured data

## 📈 Expected Project Outcomes

This analysis helps organize customer information and investigate patterns related to churn, complaints, payment preferences, and purchasing behavior. The results can support further investigation into customer retention strategies and improvements to the e-commerce customer experience.

## 🚀 Conclusion

The project demonstrates the use of MySQL for practical business data analysis. By applying data cleaning, transformation, aggregation, subqueries, and joins, the analysis explores important factors related to customer behavior and churn.

## 👩‍💻 Author

**Varsha C P**

Aspiring Data Analyst

**Technical Skills:** MySQL | Microsoft Excel | Power BI | Python | Power Query | Data Analysis


