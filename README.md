# Task-6-Aggegrate_Function
Analyzing sales data using Aggerate functions
# Task 6: Sales Trend Analysis Using Aggregations

## 🎯 Objective
The objective of this task is to analyze monthly revenue and order volume from the e-commerce dataset using SQL aggregate functions.

---

## 🧠 Key Learnings
- How to group data by **month** and **year**
- How to use SQL **aggregate functions**
- How to calculate **total revenue, total orders, average order value, min and max order values**
- How to identify **monthly trends** in sales performance

---

## 🧩 Dataset Details
**Table Name:** `ecommerce_data`  
**Columns Used:**
- `InvoiceNo` → Order number (used to count total orders)
- `InvoiceDate` → Date and time of the order
- `Quantity` → Units purchased
- `UnitPrice` → Price per unit
- `Country` → Customer’s country

-

## ⚙️ Tools Used
- **MySQL Workbench**
- **CSV dataset:** `Ecom.csv`

- 🔍 Insights

The total revenue generated shows strong sales performance across multiple countries.
UK and a few other countries recorded the highest single-order revenues, while smaller markets had minimal sales.
The average order value remained stable, indicating consistent customer spending behavior.
Daily order count shows steady customer activity, with some peak days indicating higher engagement.
Monthly analysis reveals noticeable fluctuations in revenue — likely due to seasonal demand or promotional periods.
The use of aggregate functions (SUM, COUNT, AVG, MIN, MAX) provided clear insights into sales trends, customer activity, and revenue distribution.
(InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country);
