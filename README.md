# 🚀 30 Days of Pandas – LeetCode Challenge

## 📌 About
This repository contains my daily solutions to the **LeetCode 30 Days of Pandas Challenge**.

The goal of this challenge is to strengthen my **data analysis and data manipulation skills** using **Python and Pandas** by solving real-world problems consistently every day.

This project is part of my preparation for **Data Analyst / Data Science roles**.

---

## 🧠 Skills Practiced
✔ Data Filtering  
✔ Data Cleaning  
✔ GroupBy & Aggregation  
✔ Sorting & Ranking  
✔ Merge / Join operations  
✔ Handling Missing Values  
✔ Feature Engineering  
✔ Exploratory Data Analysis (EDA)

---

## 🛠 Tech Stack
- Python
- Pandas
- Jupyter Notebook
- LeetCode

---

## 📂 Repository Structure

30-Days-of-Pandas/
│
├── Day01_Filtering/
├── Day02_GroupBy/
├── Day03_Aggregation/
├── Day04_Merge_Join/
├── Day05_Sampling/
├── ...
├── datasets/
└── README.md

Each folder contains:
- solution.py
- explanation.md

---

## 🎯 Challenge Goal
📅 Solve 1 Pandas problem daily for 30 days  
📈 Improve speed + logic building  
💼 Build a strong GitHub portfolio  
🧩 Prepare for Data Analyst interviews  

---

## ✨ Sample Solution

```python
def find_products(products):
    return products.loc[
        (products.low_fats == 'y') & (products.recyclable == 'y'),
        ['product_id']
    ]

