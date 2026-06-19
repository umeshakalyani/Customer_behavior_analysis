CUSTOMER SHOPPING BEHAVIOR ANALYSIS USING PYTHON, MYSQL AND POWER BI
ABSTRACT
Customer behavior analysis helps businesses understand purchasing patterns, customer preferences, and revenue trends. This project analyzes customer shopping behavior using Python for data preprocessing and exploratory data analysis (EDA), MySQL for business-oriented querying, and Power BI for interactive dashboard visualization. The project aims to identify customer segments, product performance, subscription impact, and purchasing trends that can support data-driven business decisions.

INTRODUCTION

Customer analytics plays a crucial role in understanding customer preferences and improving business performance. By analyzing shopping behavior data, organizations can identify purchasing trends, customer demographics, and product demand patterns. This project integrates Python, MySQL, and Power BI to perform end-to-end customer behavior analysis.

Objectives

•	Analyze customer purchasing patterns.
•	Perform exploratory data analysis on customer shopping data.
•	Generate business insights using SQL queries.
•	Develop interactive dashboards using Power BI.
•	Identify factors influencing customer spending behavior.

3. DATASET DESCRIPTION

The dataset contains customer shopping transactions with attributes such as:
•	Customer ID
•	Age
•	Gender
•	Item Purchased
•	Product Category
•	Purchase Amount
•	Location
•	Size
•	Color
•	Season
•	Review Rating
•	Subscription Status
•	Shipping Type
•	Discount Applied
•	Previous Purchases
•	Payment Method
•	Frequency of Purchases
Dataset Size
•	Total Records: 3900
•	Features: 19

4. TOOLS AND TECHNOLOGIES USED

Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Jupyter Notebook
Database
•	MySQL
Visualization
•	Power BI

5. DATA PREPROCESSING

The following preprocessing activities were performed:
•	Imported dataset into Jupyter Notebook.
•	Checked data types and dataset structure.
•	Identified missing values.
•	Filled missing review ratings using category median values.
•	Standardized column names.
•	Created additional features such as Age Group.
•	Validated data consistency.

6. EXPLORATORY DATA ANALYSIS (EDA)

The EDA process included:
Customer Analysis
•	Gender distribution
•	Age distribution
•	Age group segmentation
Product Analysis
•	Most purchased products
•	Category-wise purchases
•	Product review analysis
Revenue Analysis
•	Total revenue generated
•	Revenue by category
•	Revenue by customer demographics
Subscription Analysis
•	Subscriber vs Non-subscriber behavior
•	Revenue comparison
•	Average spending comparison
Discount Analysis
•	Discount usage patterns
•	Product-wise discount rates

7. MYSQL BUSINESS ANALYSIS

The cleaned dataset was loaded into MySQL for advanced querying.
Business Questions Solved
1.	Revenue by gender.
2.	Customers spending above average purchase amount.
3.	Top-rated products.
4.	Average purchase amount by shipping type.
5.	Subscriber vs non-subscriber spending behavior.
6.	Product discount analysis.
7.	Customer segmentation.
8.	Top-selling products by category.
9.	Repeat customer analysis.
10.	Revenue contribution by age groups.
SQL Concepts Used
•	Aggregate Functions
•	GROUP BY
•	ORDER BY
•	CASE Statements
•	Subqueries
•	Common Table Expressions (CTE)
•	Window Functions

8. POWER BI DASHBOARD

An interactive Power BI dashboard was developed to visualize business insights.
Dashboard Components
•	KPI Cards
o	Total Revenue
o	Total Customers
o	Average Purchase Amount
•	Charts
o	Revenue by Gender
o	Revenue by Category
o	Customer Distribution by Age Group
o	Subscription Analysis
o	Product Performance
o	Discount Analysis
Filters
•	Gender
•	Category
•	Season
•	Subscription Status
•	Location


9. KEY FINDINGS

•	Certain product categories generated significantly higher revenue.
•	Subscriber customers showed different spending behavior compared to non-subscribers.
•	Discount campaigns influenced purchasing decisions.
•	Specific age groups contributed more to total revenue.
•	Customer loyalty positively impacted purchase frequency.



