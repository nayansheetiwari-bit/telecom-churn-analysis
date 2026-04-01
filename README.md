# 📊 Telecom Customer Churn Analysis & Dashboard

## 📌 Project Overview
Customer churn is one of the biggest challenges in the telecom industry because losing existing customers directly impacts revenue.

In this project, I worked on an **end-to-end customer churn analysis workflow**, where I first used **Python in Jupyter Notebook** to clean and prepare the dataset, and then used the cleaned data to build an **interactive Power BI dashboard** for deeper business insights.

The goal of this project was to understand:
- which customers are more likely to churn
- what services or payment methods are linked with churn
- how customer tenure impacts retention
- what business actions can reduce churn

This project helped me combine **data cleaning, exploratory analysis, and dashboard storytelling** in one complete business case.

---

## 🛠 Tools & Technologies Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit learn** 
- **Logistic Regression**
- **Jupyter Notebook**
- **Power BI**
- **DAX**
- **Git & GitHub**

---

## 🔄 Project Workflow
The project was completed in the following steps:

### 1️⃣ Data Cleaning & Preparation (Python)
Using Jupyter Notebook, I:
- loaded the telecom churn dataset
- handled missing values
- checked data types
- cleaned unnecessary columns
- transformed categorical values where required
- Built a basic Logistic Regression model
- prepared the final cleaned dataset for dashboarding

The cleaned dataset was then exported and used directly in Power BI.

---

### 2️⃣ Dashboard Building (Power BI)
Using the cleaned file, I created an interactive dashboard to track:
- total customers
- churn count
- churn rate
- tenure distribution
- contract type analysis
- payment mode trends
- internet service-based churn
- customer risk segments

The dashboard was designed to make business insights easy to understand for non-technical stakeholders.

---

## 📈 Key Insights from the Analysis
Some of the most important insights from this project were:

- Customers with **month-to-month contracts** showed the highest churn.
- **Electronic check users** had a significantly higher churn rate.
- Customers with **lower tenure** were more likely to leave early.
- **Fiber optic users** showed relatively high churn compared to other service users.
- Long-term contracts were strongly associated with better retention.

These insights can help telecom companies focus on **customer retention strategies**.

---

## 💡 Business Recommendations
Based on the findings, some useful business recommendations are:

- offer discounts for long-term contracts
- improve onboarding experience for new customers
- create special retention campaigns for high-risk payment groups
- improve service quality for fiber optic users
- build loyalty benefits for customers in early tenure stages

---

## 📷 Dashboard Preview
### Dashboard View 1
![Dashboard 1](screenshots/Screenshot%20(397).png)

### Dashboard View 2
![Dashboard 2](screenshots/Screenshot%20(398).png)

### Dashboard View 3
![Dashboard 3](screenshots/Screenshot%20(399).png)

---

## 🎯 What I Learned
Through this project, I improved my skills in:
- data cleaning and preprocessing using Python
- handling real-world telecom customer data
- exporting clean datasets for BI tools
- building interactive dashboards in Power BI
- KPI design and business storytelling
- identifying customer churn patterns and risk drivers

## 📂 Project Structure
```text
telecom-churn-analysis
│
├── data
├── notebook
├── powerbi
├── screenshots
└── README.md

