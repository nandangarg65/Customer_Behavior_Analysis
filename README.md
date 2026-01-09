# 🛒 Customer Shopping Behavior Analysis & Dashboard

An end-to-end data analytics project analyzing **3,900 customer purchases** to uncover actionable business insights.  
This project integrates **Python, PostgreSQL, and Power BI** to help businesses make data-driven decisions.

---

## 📊 Project Overview

The goal of this project is to analyze customer shopping behavior across multiple dimensions such as:
- Demographics
- Product categories
- Subscriptions
- Discounts
- Ratings

The insights are presented through an **interactive Power BI dashboard** for easy exploration and strategic decision-making.

---

## 🗂 Dataset Summary

| Metric | Value |
|------|------|
| Total Purchases | 3,900 |
| Data Columns | 18 |
| Locations Covered | 50 |
| Products | 25 |

---

## 🛠 Tech Stack

- **Python** (Pandas, NumPy)
- **PostgreSQL**
- **Power BI**
- **Git & GitHub**

---

## 🔄 Data Preparation Workflow

1. **Data Loading & Exploration**
   - Dataset inspected using `df.info()` and summary statistics.

2. **Missing Data Handling**
   - Filled **37 missing review ratings** using category-wise median values.

3. **Feature Engineering**
   - Created new features:
     - `age_group`
     - `purchase_frequency_days`

4. **Database Integration**
   - Connected Python with **PostgreSQL** for advanced SQL-based analysis.

---

## 📈 Key Insights

### 💰 Revenue Analysis
- Male customers contribute **68% of total revenue**, more than double that of female customers.
- Indicates strong potential for **targeted marketing strategies**.

### 👥 Customer Segmentation
- **Loyal Customers:** 3,116 (80%)
- **Returning Customers:** 701
- **New Customers:** 83

➡ Retention is strong, while new customer acquisition presents a growth opportunity.

---

## ⭐ Top-Rated Products

| Product | Average Rating |
|------|------|
| Gloves | 3.86 |
| Sandals | 3.84 |
| Boots | 3.82 |
| Hat | 3.80 |
| Skirt | 3.78 |

---

## 🔁 Subscription Insights

- **Subscribers:** 27% (1,053 customers)
- **Non-Subscribers:** 73% (2,847 customers)

**Average Spend**
- Subscribers: $59.49  
- Non-subscribers: $59.87  

➡ Minimal difference suggests **subscription benefits are underutilized**.

---

## 🔖 Discount Impact

High discount dependency observed in:
- Hats (50%)
- Sneakers (49.7%)
- Coats (49.1%)
- Sweaters (48.2%)
- Pants (47.4%)

**839 customers used discounts but still spent above average**, indicating opportunities to optimize discount strategies.

---

## 📊 Power BI Dashboard

The interactive dashboard visualizes:
- Customer count and average purchase value
- Subscription distribution
- Revenue and sales by category
- Sales and revenue by age group
- Filters for gender, category, shipping type, and subscription status

---

## 🎯 Strategic Recommendations

- **Boost Subscriptions**  
  Introduce exclusive benefits to convert non-subscribers.

- **Strengthen Loyalty Programs**  
  Reward repeat customers to maintain high retention.

- **Optimize Discounts**  
  Balance sales growth with profit margins.

- **Targeted Marketing**  
  Focus on high-revenue segments and top-rated products.

---
