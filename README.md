# 📉 Customer Churn Exploratory Data Analysis (EDA)

## 📌 Project Overview
Customer retention is one of the most critical metrics for business sustainability. This project focuses on **Exploratory Data Analysis (EDA)** of a customer churn dataset to understand the key drivers behind customer attrition.

The analysis revealed an **overall churn rate of approximately 26.54%**, indicating a significant retention challenge that requires immediate strategic intervention.

---

## 📂 Dataset Description
The dataset contains customer details including:
- **Demographics:** Gender, Age range (Senior Citizen), Partners, Dependents.
- **Services:** Phone, Internet (DSL/Fiber), Security, Backup, Streaming, etc.
- **Account Info:** Contract Type (Month-to-month, One year, Two year), Payment Method, Monthly Charges.
- **Target Variable:** `Churn` (Yes/No).

---

## 🛠 Tech Stack
- **Python** (Data Analysis)
- **Pandas & NumPy** (Data Cleaning & Manipulation)
- **Matplotlib & Seaborn** (Data Visualization)
- **Jupyter Notebook** (Interactive Analysis)

---

## 🔍 Key Analysis & Insights
*Major findings derived from the analysis:*

### 1. The Senior Citizen Risk Factor
While gender showed minimal impact on churn, **Senior Citizens** are a high-risk demographic.
- **Insight:** Senior citizens have a churn rate of **42%**, compared to just **24%** for non-senior citizens. This suggests current service plans may not be meeting the needs of older adults.

### 2. Service & Infrastructure Issues
- **Fiber Optic:** Customers with Fiber Optic internet showed a high churn rate of **40%**, significantly higher than DSL users. This points to potential reliability issues or price sensitivity.
- **Support Services:** There is a strong correlation between churn and the lack of add-on support. Approximately **40% of customers** who did *not* subscribe to **Online Security** or **Tech Support** ended up churning.

### 3. Contract & Payment Frictions
- **Contract Type:** As expected, customers on **Month-to-Month contracts** churn at substantially higher rates than those on 1-Year or 2-Year commitments.
- **Payment Method:** The **"Electronic Check"** payment method is associated with the highest churn rate, whereas automatic transfers (Credit Card/Bank Transfer) show much higher stability.

---

## 📊 Recommendations
Based on the data, the following strategies are recommended to reduce the 26.54% churn rate:
1. **Targeted Senior Support:** Develop a simplified, high-support tier specifically for the Senior Citizen demographic to bring their 42% churn rate down.
2. **Push for Auto-Pay:** Incentivize users to switch from "Electronic Check" to Credit Card/Bank Transfer to increase payment stickiness.
3. **Bundle Security Services:** Since customers without Online Security are 40% likely to leave, include basic security features in the standard Fiber Optic package to add value.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/shivangsagwaliya/Customer_Churn_EDA.git](https://github.com/shivangsagwaliya/Customer_Churn_EDA.git)
