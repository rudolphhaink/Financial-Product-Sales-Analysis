# Banking Revenue Insights: A Data Analyst Portfolio Project

This project simulates a real-world sales analysis in the **banking sector**, focusing on product performance, customer acquisition, churn, and revenue generation. Using synthetic data spanning **3 years (2021–2023)**, the project combines SQL-style exploration, **linear regression in Python**, and **interactive Tableau dashboards** to uncover actionable insights.

---

## 📊 Project Objectives

- Analyze sales performance of banking products across different regions
- Explore customer acquisition trends, churn rates, and marketing ROI
- Build a **linear regression model** to predict monthly revenue
- Develop an **interactive Tableau dashboard** for data storytelling

---

## 🗃️ Dataset Overview

The dataset was synthetically generated and includes:

| Column               | Description |
|----------------------|-------------|
| `date`               | Month and year (YYYY-MM) |
| `region`             | North, South, East, West |
| `product_type`       | Credit Card, Mortgage, etc. |
| `product_name`       | e.g., "Platinum Card", "Home Loan Pro" |
| `customers_acquired` | New customers acquired that month |
| `avg_product_value`  | Avg revenue per customer |
| `marketing_spend`    | Monthly marketing budget |
| `churn_rate`         | % of customers lost |
| `revenue`            | Derived: customers × value × (1 – churn) |

> 📁 [Download the dataset](./banking_sales_data.csv)

---

## 🧪 Regression Analysis (Python)

Using `scikit-learn`, I built a **linear regression model** to predict `revenue` using:

- `marketing_spend`
- `churn_rate`
- `product_type` (one-hot encoded)
- `region`
- Seasonality factors (month/quarter)

### Key Outputs
- R² score
- Coefficient interpretation
- Residual analysis

📓 [View Jupyter Notebook →](./banking_regression_analysis.ipynb)

---

## 📈 Tableau Dashboard

The dashboard offers an interactive view into:

- 📍 Revenue by region and product
- 📉 Churn and customer acquisition trends
- 📦 Product performance over time
- 📊 Marketing spend vs. revenue
- 🔮 Forecasted revenue (from regression)

📊 [View Tableau Dashboard](#)

---

## 🛠️ Tools Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn)
- Jupyter Notebook
- Tableau
- Git & GitHub

---

## 📌 Key Learnings

- Built a complete end-to-end analysis pipeline from data wrangling to storytelling
- Applied regression modeling to real-world business metrics
- Gained practice in presenting business insights visually

---

## 🤝 Let’s Connect

Feel free to [connect with me on LinkedIn]([#](https://www.linkedin.com/in/rudolph-haink-a5454564/))!

