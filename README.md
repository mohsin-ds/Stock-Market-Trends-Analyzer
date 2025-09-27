# 📈 Stock Market Trends Analyzer

## 📌 Project Overview

The **Stock Market Trends Analyzer** explores historical stock data of **Tesla (TSLA)** using **NumPy, Pandas, and Matplotlib**.

This project covers:

1. **Data Cleaning** → parsing dates, extracting year & month.
2. **Exploratory Data Analysis (EDA)** → stock prices, moving averages, and returns.
3. **Statistical Analysis** → max, min, average price, and volatility.
4. **Data Visualization** → line charts, histograms, and bar charts.
5. **Exporting Results** → cleaned dataset saved as CSV.

---

## 📂 Dataset Information

* **Source**: https://www.kaggle.com/datasets/varpit94/tesla-stock-data-updated-till-28jun2021
* **Columns Used**:

  * `Date` → Trading date
  * `Open` → Opening price
  * `High` → Highest price
  * `Low` → Lowest price
  * `Close` → Closing price
  * `Adj Close` → Adjusted closing price
  * `Volume` → Number of shares traded

---

## 🛠️ Technologies Used

* **Python 3**
* **NumPy** → statistical calculations (max, min, mean, std dev)
* **Pandas** → data cleaning, feature extraction, rolling averages
* **Matplotlib** → financial visualizations

---

## 📑 Analysis Performed

✔️ Daily returns calculation

✔️ 50-day and 200-day moving averages

✔️ Max, Min, Average stock price

✔️ Volatility (standard deviation of returns)

✔️ Monthly average close price

---

## 📊 Visualizations

The project generates the following charts:

* 📈 **Line Chart** → Stock price with 50-day & 200-day moving averages
* 📉 **Histogram** → Distribution of daily returns
* 📊 **Bar Chart** → Monthly average close price

---

## 📂 Files in Repository

* `TSLA.csv` → Raw Tesla stock dataset from Yahoo Finance
* `stocks_cleaned.csv` → Cleaned dataset with new features (Daily Return, MA50, MA200)
* `Stock_Market_Analyzer.ipynb` → Jupyter Notebook with analysis & visualizations
* `README.md` → Project documentation

---

## 🚀 How to Run

1. Clone this repository

   ```bash
   git clone https://github.com/mohsin-ds/Stock-Market-Trends-Analyzer.git
   cd stock-market-analyzer
   ```
2. Install dependencies

   ```bash
   pip install pandas numpy matplotlib jupyter
   ```
3. Open Jupyter Notebook

   ```bash
   jupyter notebook Stock_Market_Analyzer.ipynb
   ```

---

✨ Author: **Muhammad Mohsin** (BS Software Engineering Student, Sir Syed CASE Institute of Technology, Islamabad)
🔗 GitHub: [mohsin-ds](https://github.com/mohsin-ds)

---
