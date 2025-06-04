# **Financial Risk & Market Analysis using Python**

## 📌 **Project Overview**
This repository contains two key financial analysis projects:

1. **Corporate Default Prediction** – A machine learning model to predict whether a company will default on its financial obligations using balance sheet data.
2. **Market Risk Analysis** – A statistical analysis of Indian stock market data to evaluate risk and return trends for better investment decisions.

Both projects utilize **Python and machine learning techniques** to derive insights that assist businesses and investors in making data-driven financial decisions.

---

## 🏢 **Part A: Corporate Default Prediction**

### **📖 Problem Statement**
Businesses risk default if they fail to meet debt obligations. Defaulting leads to **lower credit ratings**, **higher interest rates**, and **reduced borrowing capacity**. Investors need to identify financially stable companies before making investment decisions.

A company’s **balance sheet** provides crucial insights into its financial health, detailing **assets, liabilities, and shareholder equity**. Using **machine learning**, we predict a company's likelihood of default based on its financial statements.

### **🛠 Methodology**
- Used **Logistic Regression** as the predictive model.
- Split the dataset into **67% training** and **33% testing** (`random_state=42`).
- Evaluated performance based on **accuracy, precision, recall, and AUC scores**.

### **📊 Key Findings**
- The Logistic Regression model with an **optimal threshold of 0.1076** showed:
  - **84% accuracy** on training data.
  - **83.5% accuracy** on test data.
  - Stable and consistent predictions across both datasets.
- Precision and recall values for **default** and **non-default cases** were balanced, making the model reliable.

### **📌 Recommendations**
✔ **Collect more data** on default cases to improve prediction accuracy.
✔ **Feature engineering** could help enhance model performance.
✔ **Ensemble methods (Boosting/Bagging)** can be explored to improve default identification.

---

## 📈 **Part B: Market Risk Analysis**

### **📖 Problem Statement**
This project analyzes **6 years of weekly stock data** from **10 Indian companies** to measure market risk using **mean and standard deviation of stock returns**. The objective is to gain insights into **investment opportunities and risk factors**.

### **🛠 Methodology**
- Calculated **mean returns** and **standard deviation** for each stock.
- Identified high and low-risk stocks based on their **return volatility**.
- Used **Python (Pandas, NumPy, Matplotlib, Seaborn)** for data analysis and visualization.

### **📊 Key Findings**
- **Infosys & Shree Cement** had the **highest mean returns**, making them potential investment opportunities.
- **Idea Vodafone & Jet Airways** had the **lowest mean returns**, suggesting higher risk for investors.

### **📌 Recommendations**
✔ Investors seeking **higher profits** should consider **Infosys & Shree Cement**.
✔ Investors preferring **lower risk** should be **cautious** with **Idea Vodafone & Jet Airways**.
✔ Holding investments **long-term** can help ride out **market volatility**.
✔ Regularly **monitor market trends** to make informed investment decisions.

---

## 🛠 **Technologies Used**
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **SQL** for data manipulation
- **Machine Learning (Logistic Regression)**
- **Data Visualization & Statistical Analysis**

