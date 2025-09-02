# 🏦 Banking Analytics & Risk Dashboard – Power BI & Python Project  

This project integrates **Python, Power BI, and data visualization techniques** to analyze banking operations.  
It processes multiple datasets, derives **risk-related KPIs**, and builds **interactive dashboards** to support loan approvals, deposit monitoring, and client engagement tracking.  

---

## 📌 Project Objective  

To answer key **banking and financial questions** such as:  
- How many unique clients are engaged with the bank?  
- What is the total value of loans, deposits, and fees collected?  
- Which income bands or nationalities hold the highest loan amounts?  
- How long have clients been associated with the bank?  
- What is the contribution of different account types (checking, savings, foreign currency)?  

---

## 🧰 Tools & Technologies  

- **Language**: Python  
- **Visualization**: Power BI  
- **Libraries**: pandas, numpy, matplotlib, seaborn  
- **Data Files**: CSV, Excel (`Banking.csv`, `clients.csv`, `Banking.xlsx`)  
- **Environment**: Jupyter Notebook, Power BI Desktop  

---

## 📊 Dataset Overview  

- **Source**: Banking transaction and client datasets (CSV & Excel).  
- **Tables Used**:  
  - `Clients-Banking` → Deposits, loans, credit card balances, fees  
  - `Banking Relationship` → Client-bank associations  
  - `Gender` & `Nationality` → Demographics segmentation  
  - `Investment Advisor` → Advisory details  
  - `Period` → Engagement timelines  

---

## 🔍 Workflow  

1. **Data Preparation**  
   - Cleaned raw banking datasets (CSV/Excel).  
   - Derived new features:  
     - `Engagement_Days` (duration of client relationship)  
     - `Income_Band` (Low, Mid, High)  
     - `Processing_Fees` based on fee structure.  

2. **KPI Calculation**  
   - Built DAX measures in Power BI for:  
     - Total Clients  
     - Total Loan & Deposits  
     - Total Fees  
     - Account balances by type (Checking, Savings, Foreign Currency).  

3. **Dashboard Development**  
   - Designed **Loan Analysis**, **Deposit Analysis**, and **Summary Dashboards** in Power BI.  
   - Incorporated slicers and filters for client segmentation by income, nationality, and account type.  

4. **Exploratory Data Analysis (EDA)**  
   - Used Python notebooks for preprocessing and validation.  
   - Created curated datasets for integration into Power BI dashboards.  

---

## 📈 Analysis Performed  

### 🔹 Basic Metrics  
- Unique clients in the banking system.  
- Total loan amounts segmented by type (bank loan, business lending, credit card).  
- Total deposits across account types.  
- Processing fees generated per client.  

### 🔹 Intermediate Analysis  
- Loan distribution by income band.  
- Loan amounts grouped by nationality.  
- Engagement length of clients with the bank.  
- Balance contributions from checking vs. savings vs. foreign accounts.  

### 🔹 Advanced Insights  
- Identification of **high-risk client segments**.  
- Comparison between private vs. public bank client counts.  
- Fee impact on overall loan profitability.  
- Detection of top contributing nationalities to bank loan portfolios.  

---

## 📌 Key Findings  

- **188 unique clients** were identified in the dataset.  
- Total Loan amounted to **$139.9M**, while Total Deposits reached **$111.49M**.  
- Processing Fees generated **$5.17M** in revenue.  
- Clients with **higher income bands** contributed significantly more to loan volumes.  
- **Private banks** showed larger client bases compared to public banks.  
- Engagement analysis revealed clear patterns in **long-term vs. short-term clients**.  

---

## 📍 Conclusion  

This project demonstrates how **Power BI + Python** can:  
- Automate preprocessing of financial datasets.  
- Provide **decision-ready KPIs** on clients, deposits, and loans.  
- Enhance visibility into risk through engagement and demographic segmentation.  
- Support banking institutions in **credit approvals, strategy building, and revenue tracking**.  

