# Task-6
Here’s a sample `README.md` file for your GitHub repository based on **Task 6: Sales Trend Analysis Using Aggregations**:

---

# 📊 Sales Trend Analysis Using Aggregations

This repository contains the solution for **Task 6** of the **Data Analyst Internship** — analyzing sales trends using SQL.

# Task Overview

**Objective:**
Analyze **monthly revenue** and **order volume** using SQL aggregation functions.

**Dataset:**
`online_sales` table with the following relevant columns:

* `order_date`
* `amount`
* `product_id`
* `order_id`

# Tools Used

* SQL (MySQL)

# Key SQL Concepts Used

* `EXTRACT(MONTH FROM order_date)` for extracting the month.
* `GROUP BY` clause to group data by year and month.
* `SUM(amount)` to calculate revenue.
* `COUNT(DISTINCT order_id)` to count unique orders (volume).
* `ORDER BY` to sort results.
* `LIMIT` to get top months.
```

# Output Example

| Year | Month | Revenue | Order Volume |
| ---- | ----- | ------- | ------------ |
| 2023 | Jan   | 14500   | 87           |
| 2023 | Feb   | 13750   | 81           |
| ...  | ...   | ...     | ...          |

