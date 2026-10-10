# 🛍️ Retail Sales Analysis Using SQL

![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue)
![Data Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-orange)
![Project Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

The **Retail Sales Analysis Using SQL** project focuses on analyzing retail transaction data to understand sales performance, customer purchasing patterns, product category performance, and order distribution across different time periods.

Using SQL, I explored the dataset, checked data quality, handled missing values, and answered 10 business questions to derive useful insights from retail sales data.

This project demonstrates the practical application of SQL for data cleaning, data exploration, aggregation, and business analysis.

## 🎯 Project Objectives

- Analyze overall retail sales performance.
- Identify sales performance across product categories.
- Understand customer purchasing behavior.
- Calculate average customer age for a specific product category.
- Identify top 5 customers based on total sales.
- Analyze the best-selling month in each year based on average transaction value.
- Understand order distribution across morning, afternoon, and evening shifts.
- Practice writing SQL queries to solve real-world business problems.

## 🛠️ Tools & Technologies

- **SQL** — Data cleaning, querying, and analysis
- **PostgreSQL** — SQL functions, date extraction, and analytical queries
- **CSV** — Retail sales dataset
- **GitHub** — Project hosting and version control

## 📂 Dataset Description

The project uses a retail sales dataset containing **2,000 rows and 11 columns**.

| Column | Description |
|---|---|
| `transactions_id` | Unique transaction identifier |
| `sale_date` | Date of the transaction |
| `sale_time` | Time of the transaction |
| `customer_id` | Customer identifier |
| `gender` | Customer gender |
| `age` | Customer age |
| `category` | Product category |
| `quantiy` | Quantity purchased |
| `price_per_unit` | Price per unit |
| `cogs` | Cost of goods sold |
| `total_sale` | Total transaction value |

The dataset contains three product categories: Clothing, Electronics, and Beauty.

## 🧹 Data Cleaning

Before performing the analysis, I used SQL to check and improve data quality.

- Inspected the dataset using `SELECT` and `LIMIT`.
- Checked for missing values using `IS NULL`.
- Removed records containing NULL values in selected important columns.
- Explored the dataset using aggregate and distinct-value queries.

## 📊 SQL Analysis & Business Questions

The project answers the following 10 business questions:

**1. Sales on a Specific Date**

Retrieve all transaction details for sales made on November 5, 2022.

**2. Clothing Sales Analysis**

Identify Clothing transactions in November 2022 where the quantity purchased is at least 4 units.

**3. Category-Wise Sales Performance**

Calculate total sales and the number of orders for each product category using `SUM()`, `COUNT()`, and `GROUP BY`.

**4. Average Customer Age**

Find the average age of customers purchasing products from the Beauty category using `AVG()` and `ROUND()`.

**5. High-Value Transactions**

Retrieve transactions with a total sales value of at least 1,000.

**6. Gender-Wise Transaction Analysis**

Calculate the number of transactions for each gender within each product category.

**7. Best-Selling Month in Each Year**

Calculate the average transaction value for each month and rank the months within each year using `RANK()` and window functions.

**8. Top 5 Customers**

Identify the five customers with the highest cumulative sales using `SUM()`, `GROUP BY`, `ORDER BY`, and `LIMIT`.

**9. Unique Customers by Category**

Count distinct customers who purchased products from each category using `COUNT(DISTINCT customer_id)`.

**10. Shift-Wise Order Analysis**

Classify transactions into Morning, Afternoon, and Evening shifts using `CASE` and `EXTRACT()`, then calculate the number of orders in each shift using a Common Table Expression (CTE).

## 💡 Key SQL Concepts Used

- `SELECT`, `WHERE`, and `LIMIT`
- `COUNT()`, `SUM()`, `AVG()`, and `ROUND()`
- `GROUP BY` and `ORDER BY`
- `DISTINCT` and `COUNT(DISTINCT)`
- `IS NULL` and `DELETE`
- Date and time functions: `TO_CHAR()` and `EXTRACT()`
- Conditional logic: `CASE WHEN`
- Common Table Expressions (CTEs)
- Window functions: `RANK()` and `PARTITION BY`
- Subqueries and filtering ranked results

## 📈 Key Learning Outcomes

Through this project, I strengthened my ability to:

- Clean and explore structured datasets using SQL.
- Write queries to answer business-related questions.
- Aggregate and compare sales across product categories.
- Analyze customer purchasing behavior.
- Use date and time functions for time-based analysis.
- Apply window functions and CTEs to solve analytical problems.
- Translate raw data into meaningful business information.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open PostgreSQL or a compatible SQL editor.
3. Create the `retail_sales` table using the SQL script.
4. Import the provided CSV dataset into the table, mapping the CSV columns to the table columns correctly.
5. Execute the SQL queries to perform the analysis.
6. Review the query results to explore the business questions and their answers.

## 📁 Repository Structure

```text
Retail-sales-analysis-by-sql/
│
├── retail_sql_project.sql
├── SQL - Retail Sales Analysis_utf.csv
└── README.md
```

*The filenames above describe the intended project structure; adjust them to match the actual names in the repository.*

## 👨‍💻 About Me

I am an aspiring Data Analyst interested in SQL, Python, Power BI, and Machine Learning. I enjoy working on practical projects that help me improve my data analysis and problem-solving skills.

🔗 **GitHub Repository:**  
https://github.com/thekamesh/Retail-sales-analysis-by-sql

---
