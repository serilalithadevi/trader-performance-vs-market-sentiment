# 📈 Trader Performance vs Market Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B?logo=streamlit)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

# Trader Performance vs Market Sentiment

**Primetrade.ai – Data Science / Analytics Internship Assignment**

👩‍💻 **Author:** Lalitha Devi Seri

📧 **Email:** serilalithadevi@gmail.com

🔗 **LinkedIn:** https://www.linkedin.com/in/lalitha-devi-seri/

💻 **GitHub:** https://github.com/serilalithadevi

---

# 📌 Project Overview

This project explores how Bitcoin market sentiment influences trader behaviour and performance by combining the **Fear & Greed Index** with **Hyperliquid historical trading data**.

The project demonstrates an end-to-end Data Analytics workflow including:

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Trader Segmentation
- Predictive Modeling
- Interactive Streamlit Dashboard

---

# 🎯 Objectives

- Analyze trader profitability across different market sentiment conditions.
- Compare trader behaviour during Fear and Greed markets.
- Engineer meaningful trading metrics.
- Identify trader segments using K-Means clustering.
- Build a predictive model for trader profitability.
- Develop an interactive Streamlit dashboard.

---

# 📂 Datasets

The datasets were provided as part of the Primetrade.ai internship assignment.

### 1. Bitcoin Fear & Greed Index

https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

### 2. Hyperliquid Historical Trader Data

https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

> **Note:** The original datasets exceed GitHub's web upload size limit (25 MB). Therefore, the repository includes the engineered dataset (`master_df.csv`) while the original datasets are referenced through their Google Drive links.

---

# 📁 Repository Structure

```
trader-performance-vs-market-sentiment/
│
├── README.md
├── Trader_Performance_Analysis.ipynb
├── master_df.csv
├── requirements.txt
```

---

# ⚙️ Setup

Clone the repository

```bash
git clone https://github.com/serilalithadevi/trader-performance-vs-market-sentiment.git

cd trader-performance-vs-market-sentiment
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ How to Run

### Run the Notebook

```bash
jupyter notebook
```

Open

```
Trader_Performance_Analysis.ipynb
```

Run all cells sequentially.

### Run the Streamlit Dashboard

```bash
python -m streamlit run app.py
```

---

# 📊 Methodology

1. Loaded and validated both datasets.
2. Performed missing value and duplicate analysis.
3. Converted timestamps and aligned datasets by trading date.
4. Engineered key trading metrics including:
   - Daily PnL
   - Win Rate
   - Average Trade Size
   - Number of Trades
   - Long/Short Ratio
5. Compared trader performance across different market sentiment conditions.
6. Analysed behavioural changes under Fear and Greed markets.
7. Applied K-Means clustering to identify trader segments.
8. Built a Random Forest classifier to predict trader profitability.
9. Developed a lightweight Streamlit dashboard for interactive exploration.

---

# 📊 Key Insights

- Trader profitability varied significantly across market sentiment conditions.
- Fear markets exhibited higher trading activity and larger average trade sizes.
- Extreme Greed achieved the highest average win rate.
- Market sentiment strongly influenced trader behaviour and decision-making.
- Behavioural clustering revealed distinct trader profiles with different performance characteristics.

---

# 💡 Strategy Recommendations

### Strategy 1
Increase trading activity during Fear markets while maintaining disciplined risk management.

### Strategy 2
Prioritize high-conviction trades during Greed markets instead of increasing trading frequency.

### Strategy 3
Incorporate the Fear & Greed Index into trading decisions to dynamically adjust position sizing and trading behaviour.

---

# 🤖 Machine Learning

A Random Forest classifier was developed to predict trader profitability using engineered behavioural features and market sentiment.

---

# 👥 Trader Segmentation

K-Means clustering was used to group traders based on:

- Daily PnL
- Win Rate
- Trading Frequency
- Average Trade Size

---

# 📈 Interactive Dashboard

The project also includes a lightweight Streamlit dashboard for interactive exploration of trader performance.

Features include:

- Market Sentiment Filter
- Performance Summary
- Daily PnL Analysis
- Win Rate Analysis
- Average Trade Size Analysis

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Streamlit
- Jupyter Notebook

---

# 📚 References

- Primetrade.ai Internship Assignment
- https://alternative.me/crypto/fear-and-greed-index/
- https://pandas.pydata.org/
- https://numpy.org/
- https://matplotlib.org/
- https://scikit-learn.org/
- https://streamlit.io/

---

# ⭐ Thank You

Thank you for reviewing this project.

I appreciate your time and look forward to the opportunity to discuss my analysis and findings during the interview.
