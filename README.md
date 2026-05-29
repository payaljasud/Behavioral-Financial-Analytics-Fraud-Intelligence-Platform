# Behavioral-Financial-Analytics-Fraud-Intelligence-Platform
## Project Overview
End-to-end analytics pipeline for detecting anomalous transaction patterns and segmenting customer behavior using unsupervised ML. Built with Snowflake, Isolation Forest, and Power BI.
This project focuses on analyzing financial transaction behavior and identifying potentially fraudulent activities using data analytics and unsupervised machine learning techniques. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, anomaly detection, and dashboard visualization.
The project was built to understand how transaction patterns can be used to detect unusual behavior and generate meaningful business insights from financial datasets.

---
## Dataset Information

This project uses the **PaySim mobile money transaction dataset** (synthetic financial data).
https://www.kaggle.com/datasets/ealaxi/paysim1?resource=download
I worked with PaySim's 6.3M transaction dataset. For initial feature engineering, I used stratified sampling to maintain fraud rate while reducing computation time by 99%

---

## Objectives

* Analyze transaction behavior patterns using EDA
* Clean and preprocess raw financial transaction data
* Engineer behavioral features for fraud analysis
* Detect anomalous transactions using Isolation Forest
* Visualize insights through interactive Power BI dashboards

---

## Tech Stack

| Category         | Technologies                    |
| ---------------- | ------------------------------- |
| Programming      | Python, SQL                     |
| Data Processing  | Pandas, NumPy, PySpark          |
| Machine Learning | Scikit-learn (Isolation Forest) |
| Visualization    | Matplotlib, Seaborn, Power BI   |
| Tools            | Jupyter Notebook, Git, GitHub   |
| Database         | Snowflake (Foundational)        |

---

## Workflow

```text
Raw Transaction Data
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis (EDA)
        ↓
Feature Engineering
        ↓
Anomaly Detection using Isolation Forest
        ↓
Power BI Dashboard & Insights
```

---

## Key Features

### Exploratory Data Analysis

* Analyzed transaction amount distributions and transaction types
* Identified temporal transaction patterns and behavioral trends
* Compared normal and anomalous transaction activities

### Feature Engineering

Created behavioral features such as:

* Transaction frequency
* Amount volatility
* Average transaction value
* Time-based transaction activity

### Anomaly Detection

* Applied Isolation Forest for unsupervised fraud detection
* Identified unusual transaction patterns without labeled data
* Generated anomaly scores for suspicious activities

### Dashboard Visualization

Built interactive Power BI dashboards to visualize:

* Transaction trends
* Fraud indicators
* Customer behavior patterns
* High-risk activity insights

---
---

## Results & Insights

* Detected anomalous transaction patterns using behavioral analysis
* Improved understanding of transaction trends through EDA and visualization
* Built dashboards for easier interpretation of fraud-related insights
* Explored how unsupervised learning can support fraud intelligence workflows

---

## Future Improvements

* Add real-time transaction monitoring
* Experiment with additional anomaly detection models
* Improve dashboard interactivity and reporting features
* Explore model explainability techniques

---





# What I learned
Spark window functions are powerful but memory-hungry. Snowflake's time travel is amazing for backtesting but costs credits. Next time I'd add dbt for transformation layer."
