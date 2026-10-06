# Customer Behavior Analysis

## 📌 Project Overview

This project analyzes customer transaction and behavioral data to understand purchasing patterns, customer segments, returns, and churn behavior. An interactive Power BI dashboard summarizes the results.

The objective was to identify valuable customer groups, understand their purchasing behavior, and generate actionable insights that can help improve customer retention and business performance.

---

## 🎯 Problem Statement

Businesses need to understand:

- Which customers are most valuable?
- How do customers differ in their purchasing behavior?
- Which customer segments are at risk of churn?
- Which product categories and payment methods are more frequently used?
- How do returns relate to customer churn?
- What strategies can be used to improve customer retention?

This project uses data analysis and RFM segmentation to answer these questions.

---

## 📊 Dataset

The dataset contains customer transaction and behavioral information, including attributes such as:

- Customer information
- Age
- Gender
- Product category
- Purchase amount
- Payment method
- Returns
- Churn information
- Transaction-related information

**Dataset Size:** 500,000 rows × 13 columns (about 50,000 customers, transactions from January 2020 to 2023)

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook
- Power BI

---

## 🔍 Analysis Performed

### 1. Data Cleaning
- Checked missing values
- Removed/handled duplicate records
- Corrected data types
- Prepared data for analysis

### 2. Feature Engineering
Created useful features from the transaction data, including:

- Year
- Month
- Day
- Weekday
- Revenue-related features
- Return indicators

### 3. RFM Analysis

Performed RFM (Recency, Frequency, Monetary) analysis to segment customers into groups:

- Champions
- Loyal Customers
- Potential Loyalists
- At-Risk Customers
- Others

### 4. Customer Behavior Analysis

Analyzed:

- Purchasing trends
- Product categories
- Payment methods
- Customer demographics
- Purchase frequency
- Revenue patterns

### 5. Churn & Returns Analysis

Analyzed customer churn based on:

- Customer characteristics
- Product categories
- Returns
- Purchasing behavior

---

## 📉 Power BI Dashboard

The dashboard presents the results visually and includes:

- **KPI cards:** Customer Count, Total Revenue, Transaction Count, Average Purchase, Churn Rate
- **Revenue views:** monthly trend, trend over time, by product category, by payment method
- **RFM views:** customer distribution and revenue contribution by segment
- **Churn views:** overall churn distribution, churn by product category, churn by age group
- **Demographics:** customer distribution by age group

---

## 📈 Key Findings

- The business has about 50K customers and 500K transactions, generating **$1.36bn** in revenue with an average purchase of **$2.73K**.
- **27.2%** of customers (17.92K of 50K) have churned. At transaction level, the churn rate is about 20%.
- **At-Risk** customers form the largest RFM segment (**29.3%** of customers) and still contribute about **21%** of revenue, which makes them the top retention priority.
- **Loyal Customers** generate the most revenue (about **$0.37bn**, roughly 27% of the total).
- **Champions** are the smallest group (**6.5%** of customers, about 10% of revenue) but have the highest revenue per customer (about **$43K** compared with about $27K on average).
- Churn is spread fairly evenly across age groups (about 19–21%) and across product categories, so it is not driven by age or category alone.
- **Clothing** ($0.38bn) and **Books** ($0.37bn) are the top revenue categories, while Electronics and Home each contribute about $0.31bn.
- **Credit Card** (about 37%) and **PayPal** (about 32%) lead payment methods, while **Crypto** contributes only about 5% of revenue.
- Monthly revenue stayed steady at roughly $30M from January 2020 to mid-2023. The sharp dip at the very end of the data comes from an incomplete final month, not a real decline.

---

## 💡 Business Recommendations

- Launch re-engagement campaigns for the large At-Risk segment, since it still brings in about a fifth of revenue.
- Build loyalty programs and exclusive offers for Loyal Customers and Champions.
- Give targeted offers to Potential Loyalists to move them into the Loyal segment.
- Since churn is similar across age groups and categories, focus on behavior-based signals (recency, frequency, returns) rather than demographics.
- Review Crypto payments, which bring very little revenue, and encourage the popular payment methods.
- Use RFM segments to personalize marketing campaigns.

---

## 📁 Files

- `Customer_Behavior_Analysis.ipynb` – Complete analysis notebook
- `README.md` – Project documentation

---

## 👩‍💻 Author

**Vaishnavi Tiwari**

B.Tech – Computer Science & Artificial Intelligence

Aspiring Data Analyst
