# 🍽️ Zomato Orders — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![Pandas](https://img.shields.io/badge/Pandas-EDA-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Overview
An end-to-end exploratory data analysis of Zomato restaurant data covering **148 orders** across multiple restaurant categories. This project uncovers customer behavior patterns, spending habits, and rating trends to generate actionable business insights.

---

## 📂 Project Structure
```
zomato-analysis/
│
├── Zomato_data_analysis.ipynb   # Main analysis notebook
├── Zomato data .csv             # Dataset (add your own)
└── README.md
```

---

## 🔍 Key Questions Answered
- Which restaurant type is most popular on Zomato?
- Does accepting online orders affect ratings?
- What are the spending patterns across different restaurant categories?
- Which restaurants are top and bottom rated?
- Do customers prefer booking tables in advance?

---

## 📊 Key Findings

| # | Insight |
|---|---------|
| 1 | **Dining** is the most popular restaurant category |
| 2 | Restaurants accepting **online orders** receive higher ratings |
| 3 | Most restaurants are rated between **3.5 – 4.0** |
| 4 | **Cafes** lead in online orders; Dining is mostly offline |
| 5 | Majority of customers **do not** book tables in advance |
| 6 | **Onesta** has the highest rating; Nandhini Deluxe the lowest |
| 7 | Dining has the widest cost range: ₹10 – ₹850+ for two |

---

## 🛠️ Tools & Libraries
- **Python 3.10**
- **Pandas** — data manipulation and cleaning
- **NumPy** — numerical operations
- **Matplotlib** — custom plots and charts
- **Seaborn** — statistical visualizations

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/zomato-analysis.git
   cd zomato-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Add the dataset CSV to the project folder and update the path in Cell 2.

4. Launch Jupyter:
   ```bash
   jupyter notebook Zomato_data_analysis.ipynb
   ```

---

## 📁 Dataset
- Source: [Kaggle — Zomato Dataset](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)
- Records: 148 restaurant orders
- Key columns: `name`, `rate`, `votes`, `listed_in(type)`, `online_order`, `book_table`, `approx_cost(for two people)`

---

## 👩‍💻 Author
**Neha Joshi** — Data Analyst  
[LinkedIn](#) | [GitHub](#) | [HackerRank](#)
