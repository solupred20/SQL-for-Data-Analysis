# SQL for Data Analysis

## Overview

This project demonstrates the use of SQL for analyzing an e-commerce dataset. It includes multiple queries to extract insights such as recent orders, product performance, customer value, and advanced query techniques.

## Dataset

* ecommerce.db: SQLite database containing orders, customers, products, and order_items tables

## Objectives

* Perform data extraction using SELECT statements
* Apply filtering, sorting, and joins
* Use aggregation functions for business insights
* Implement advanced SQL concepts like subqueries and views

## Queries Implemented

### 1. Recent Orders

* Retrieved recent orders after a specific date
* Joined orders with customers
* Sorted results by latest orders

### 2. Total Sales per Product

* Calculated total sales using quantity × unit price
* Grouped by product
* Ranked top-performing products

### 3. Customer Revenue (ARPU)

* Calculated total and average spending per customer
* Used aggregation with GROUP BY
* Combined multiple tables (customers, orders, order_items)

### 4. Customers with No Orders

* Used LEFT JOIN to identify customers without purchases
* Filtered NULL values

### 5. Products Above Average Sales

* Used subquery to compare product sales against average
* Demonstrated advanced filtering logic

### 6. Monthly Sales View

* Created a reusable SQL VIEW for monthly sales
* Aggregated revenue by month

### 7. Querying the View

* Retrieved monthly sales data
* Ordered results by date

### 8. Query Optimization

* Created index on order_date to improve performance

### 9. RIGHT JOIN Simulation

* Used LEFT JOIN to simulate RIGHT JOIN (SQLite limitation)

### 10. Top Customers by Spending

* Identified top 5 customers based on total spending
* Used nested queries and sorting

## Files Included

* ecommerce.db — SQLite database
* task3_queries.sql — SQL queries used in analysis
* query_1.csv — Output of Query 1
* query_1.png — Visualization of Query 1 output
* task3_README.md — Task-specific documentation

## Tools and Technologies

* SQL (SQLite)
* DB Browser for SQLite
* Python (optional for exporting results)

## Key Insights

* Customer purchasing behavior varies significantly
* A small group of customers contributes heavily to revenue
* Certain products consistently outperform others
* Monthly trends can be tracked using SQL views

## Status

Completed and ready for submission

## Author

Mohamed Moustafa
