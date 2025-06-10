# Sales-Trend-Analysis-Using-SQL-Aggregations
This task focuses on analyzing monthly sales trends using SQL queries on the online_sales dataset. The goal is to extract meaningful business insights by calculating the total revenue and number of orders placed each month.
📊 Task 6: Sales Trend Analysis Using Aggregations

📝 Overview

This task aims to perform Sales Trend Analysis using SQL to understand monthly trends in revenue and order volume. The objective is to group transactional data by month and year, apply aggregations like SUM() and COUNT(), and sort the results for insightful visualization.


---

🔧 Tools Used

Database: PostgreSQL / MySQL / SQLite

Language: SQL

Output Format: PDF

Key SQL Functions Used:

EXTRACT(YEAR FROM order_date)

EXTRACT(MONTH FROM order_date)

SUM(amount)

COUNT(DISTINCT order_id)

GROUP BY, ORDER BY




---

📁 Files Included

File Name	Description

TASK_6_Sales_Trend_Analysis.pdf	Final report including SQL script and sample results table
README.md (this file)	Project description, tools, and instructions



---

🧾 SQL Script Summary

The SQL script performs the following:

Extracts the year and month from each order's order_date.

Aggregates the total revenue using SUM(amount).

Counts unique orders using COUNT(DISTINCT order_id).

Groups the data by year and month to observe trends.

Sorts the final output by chronological order.



---

📊 Sample Output Table

Year	Month	Total Revenue	Total Orders

2023	1	INR 1,25,000	230
2023	2	INR 1,45,500	280
2023	3	INR 1,67,200	310
2023	4	INR 1,80,000	340



---

📌 Learning Outcome

Through this task, I have:

Learned how to group data using date parts (month, year).

Used aggregate functions like SUM() and COUNT() to generate business insights.

Gained confidence in writing clean and optimized SQL queries for reporting purposes.

Understood how to present SQL output in a professional PDF format for stakeholders.


## 💼 Author
*Prachee *

## Linkedin Profile: (https://www.linkedin.com/in/prachee-chahar-6637832a1)
