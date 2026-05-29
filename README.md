# 🛍️ Customer Behavior Data Analyst Portfolio Project

## 📌 Project Overview

This project is a complete **end-to-end data analytics case study** designed to simulate the real-world workflow of a professional Data Analyst in a business environment.

The objective of this project is to transform raw customer shopping data into meaningful business insights through:

* Data Cleaning & Preparation
* Exploratory Data Analysis (EDA)
* SQL-Based Business Analysis
* Interactive Dashboard Development
* Insight Generation & Strategic Recommendations

The project demonstrates analytical thinking, technical proficiency, and business intelligence skills commonly expected in modern analytics roles.

---

# 🚀 Business Problem

Retail companies generate massive amounts of customer transaction data every day. However, without proper analysis, valuable insights related to customer behavior, loyalty, purchasing patterns, and revenue drivers remain hidden.

This project aims to answer critical business questions such as:

* Which customer groups generate the highest revenue?
* How do subscriptions influence spending behavior?
* Which products receive the highest customer satisfaction?
* Do shipping preferences impact purchase amount?
* How can businesses improve customer retention and loyalty?

---

# 🛠️ Tech Stack

| Tool                 | Purpose                                   |
| -------------------- | ----------------------------------------- |
| Python               | Data Cleaning & Exploratory Data Analysis |
| Pandas & NumPy       | Data Manipulation                         |
| Matplotlib & Seaborn | Data Visualization                        |
| PostgreSQL           | SQL Analysis & Business Queries           |
| Power BI             | Interactive Dashboard                     |
| Jupyter Notebook     | Analysis Environment                      |
| Git & GitHub         | Version Control & Portfolio Hosting       |

---

# 📂 Project Workflow

## 1️⃣ Data Preparation & Cleaning (Python)

### Tasks Performed:

* Loaded and explored the dataset
* Checked data types and missing values
* Handled missing data in review ratings
* Removed inconsistencies and duplicates
* Performed feature engineering
* Created customer segments and purchase frequency groups

### Key Libraries Used:

```python
pandas
numpy
matplotlib
seaborn
```

---

# 📊 Exploratory Data Analysis (EDA)

Performed detailed analysis to identify customer purchasing behavior and revenue patterns.

### Analysis Included:

* Revenue by Gender
* Subscription Impact on Spending
* Shipping Preference Analysis
* Product Category Performance
* Discount Usage Patterns
* Customer Segmentation
* Purchase Frequency Trends

---

# 🗄️ SQL Business Analysis

The cleaned dataset was integrated into PostgreSQL to simulate real-world business analysis scenarios.

### Sample Business Questions Solved:

* Top spending customer groups
* Revenue contribution by subscription users
* Most preferred shipping types
* High-value discount customers
* Product review analysis
* Customer retention insights

### Example SQL Query

```sql
SELECT gender,
       ROUND(SUM(purchase_amount),2) AS total_revenue
FROM customer_data
GROUP BY gender
ORDER BY total_revenue DESC;
```

---

# 📈 Power BI Dashboard

An interactive dashboard was developed to visualize customer behavior trends and support business decision-making.

## Dashboard Features:

* KPI Cards
* Revenue Analysis
* Customer Segmentation
* Subscription Insights
* Product Performance
* Shipping Analysis
* Interactive Filters & Slicers

---

# 🔍 Key Insights

## 💡 Subscription Customers Spend More

Subscribers contribute significantly higher revenue compared to non-subscribers.

## 💡 Express Shipping Users Have Higher Purchase Value

Customers choosing express shipping tend to spend more per transaction.

## 💡 Female Customers Generate Slightly Higher Revenue

Revenue contribution from female customers slightly exceeds male customers.

## 💡 Discounts Attract High-Value Buyers

Certain premium customers actively purchase discounted products.

## 💡 Loyal Customers Drive Long-Term Revenue

Repeat customers contribute a major portion of total business revenue.

---

# 📌 Strategic Recommendations

### ✅ Strengthen Subscription Programs

Offer exclusive rewards and personalized benefits to increase subscriber retention.

### ✅ Improve Loyalty Programs

Encourage repeat purchases using point systems and customer rewards.

### ✅ Focus on High-Performing Products

Promote highly rated products through targeted campaigns.

### ✅ Personalized Marketing

Use customer segmentation for customized offers and recommendations.

### ✅ Optimize Shipping Strategies

Encourage premium delivery options for high-value customers.

---

# 📁 Project Structure

```bash
Customer-Behavior-Analysis/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── powerbi/
│   └── customer_dashboard.pbix
│
├── presentation/
│   └── Customer-Shopping-Behavior-Analysis.pptx
│
├── images/
│   └── dashboard_screenshots.png
│
└── README.md
```

---

# 📊 Dataset Information

* Total Records: **3,900**
* Columns: **18**
* Data Type: Customer Shopping Transactions
* Features Include:

  * Age
  * Gender
  * Product Category
  * Purchase Amount
  * Shipping Type
  * Subscription Status
  * Discount Usage
  * Review Ratings

---

# 🎯 Skills Demonstrated

## Technical Skills

* Python Programming
* SQL Query Writing
* Data Cleaning
* Data Visualization
* Dashboard Development
* Business Analysis

## Analytical Skills

* Customer Segmentation
* KPI Analysis
* Revenue Analysis
* Trend Identification
* Insight Generation

## Business Skills

* Strategic Thinking
* Data Storytelling
* Reporting & Presentation

---

# 📸 Project Preview

(Add dashboard screenshots here)

```markdown
![Dashboard Screenshot](images/dashboard.png)
```

---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

* Building complete analytics workflows
* Translating data into business insights
* Creating professional dashboards
* Writing optimized SQL queries
* Presenting analytical findings effectively

---

# 👨🏻‍💻 Author

**Supriya**
Aspiring Data Analyst | Python | SQL | Power BI

---

# ⭐ If You Like This Project

If you found this project useful, consider giving it a ⭐ on GitHub!





