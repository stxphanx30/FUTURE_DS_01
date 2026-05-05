# 📊 Customer Churn & Retention Analysis

## 🧭 Introduction

This analysis explores customer churn behavior in a subscription-based business using the Telco Customer Churn dataset.

The objective is to understand why customers leave, identify high-risk segments, and provide actionable recommendations to improve customer retention and long-term value.

The analysis includes data cleaning, feature exploration, and visualization through a Power BI dashboard.

---

## 🔍 Data Preparation & Methodology

Before conducting the analysis, the dataset was carefully cleaned to ensure accuracy:

- The `TotalCharges` column was converted from text to numeric format
- Missing values were identified and removed to maintain data integrity
- Customer attributes such as tenure, contract type, and payment methods were analyzed
- A new feature, **Customer Lifetime Value (CLV)**, was created using tenure and monthly charges
- Customers were grouped into **tenure segments** to analyze retention patterns over time

This approach ensures that insights are based on **reliable and structured customer data**.

---

## 📊 Key Findings

### 📉 Churn Overview

The dataset shows a churn rate of approximately **27%**, indicating that more than a quarter of customers leave the service.

This highlights a **significant retention challenge** for the business.

---

### 📄 Contract Type Impact

Customers on **month-to-month contracts** exhibit the highest churn rates.

In contrast, customers with **long-term contracts (1-year or 2-year)** are significantly more likely to stay.

This suggests that **customer commitment strongly influences retention**.

---

### ⏳ Customer Lifetime (Tenure)

Churn is highest among customers in their **first year (0–1 Year)**.

Customers with longer tenure show much lower churn rates, indicating that:

> The early stage of the customer lifecycle is the most critical for retention.

---

### 💳 Payment Method Behavior

Customers using **electronic check** have the highest churn rates.

More stable payment methods such as **credit card or bank transfer** are associated with better retention.

---

### 💰 Monthly Charges Influence

Customers who churn tend to have **higher average monthly charges** compared to those who stay.

This suggests that **pricing sensitivity may influence churn decisions**.

---

### 💎 Customer Value (CLV)

Customers who remain longer generate significantly higher **Customer Lifetime Value (CLV)**.

This reinforces the importance of retention in driving long-term revenue.

---

## 💡 Business Recommendations

### 🚀 1. Encourage Long-Term Contracts

Offer incentives for customers to switch from month-to-month to longer-term contracts to improve retention.

---

### 🎯 2. Focus on Early Retention

Implement onboarding programs, customer support, and engagement strategies during the **first year**, where churn risk is highest.

---

### 💳 3. Optimize Payment Experience

Encourage customers to adopt more stable payment methods such as automatic billing or credit card payments.

---

### 💰 4. Review Pricing Strategy

Analyze pricing tiers and perceived value to ensure customers feel they are receiving fair value for the cost.

---

### 👥 5. Increase Customer Engagement

Use personalized offers, loyalty programs, and proactive communication to strengthen customer relationships.

---

## Conclusion

This analysis highlights the key drivers of customer churn and identifies critical opportunities to improve retention.

By focusing on:

- Early customer engagement
- Contract strategy
- Payment behavior
- Pricing optimization

The business can reduce churn, increase customer lifetime value, and achieve more sustainable growth.

The Power BI dashboard provides an interactive view of these insights, enabling data-driven decision-making.
