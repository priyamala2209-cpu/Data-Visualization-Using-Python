# 🚕 Python-Based Data Analytics & Visualization using Matplotlib Seaborn

This project performs data cleaning, missing-value handling, exploratory data analysis, and statistical visualization on the Seaborn Taxis dataset (6433 NYC taxi trips) using Pandas, NumPy, Matplotlib, and Seaborn.

End-to-end Exploratory Data Analysis (EDA) on NYC Taxi trips using Python — from raw data cleaning to actionable business insights.

---

## 📌 Project Overview

Raw taxi data is messy and hard to interpret. This project transforms it into clear insights to understand:

How distance affects fare, tip, and total amount
Which payment methods, boroughs, and zones generate the most trips
Customer tipping behavior and toll patterns
Peak pickup times and trip patterns

---

## 🎯 Objectives

Data Loading : Load taxis dataset via sns.load_dataset("taxis")
Data Cleaning: Handle missing values (Median for numerical, Mode for categorical)
EDA: Understand shape, dtypes, info(), describe(), value_counts()
Visualization: Create insightful plots for fare, distance & customer behavior
Insights: Derive business recommendations to improve taxi operations

---

## 🛠️ Tech Stack

 Python 3.x
 Pandas - Data Manipulation
 NumPy - Numerical Operations
 Matplotlib & Seaborn - Statistical Visualization
 Jupyter Notebook

---

## 📊 Dataset - Seaborn taxis

6433 Rows x 15 Columns
Columns: pickup, dropoff, passengers, distance, fare, tip, tolls, total, color, payment, pickup_borough, pickup_zone, dropoff_borough, dropoff_zone

import seaborn as sns
df = sns.load_dataset("taxis")

---

## 🔍 Analysis Performed

1. Missing Value Handling

        Checked missing values with heatmap
        Numerical: Imputed with Median (robust to outliers)
        Categorical: Imputed with Mode (e.g., payment -> credit card)

2. Key Visualizations

        Distribution: Fare, Distance, Total amount (Histplot + KDE)
        Relationship: Distance vs Fare, Fare vs Tip (Scatter + Regplot)
        Categorical: Payment method count, Pickup borough trips (Countplot)
        Comparison: Average fare by borough (Barplot)
        Correlation: Heatmap of numerical variables
        Time Analysis: Trips by pickup month

---

## 💡 Key Insights (Example)

1. Fare is strongly positively correlated with distance.
2. Credit card is the dominant payment method (∼70%+).
3. Manhattan generates the highest number of pickups.
4. Tips are higher for credit card payments vs cash.
5. Most trips are short-distance (< 5 miles) but long trips drive higher total revenue.

---

## 📁 Project Structure

Python-Based-Taxi-Data-Analytics-Insights-Visualization/

│

├── Taxi_Data_Analysis.ipynb

├── README.md

└── visuals/ (saved plots)

---

# ▶️ How to Run the Project

## Step 1: Clone the Repository

```bash
git clone <your-github-repository-url>
```

## Step 2: Open the Project Folder

```bash
cd Data-Visualization-Using-NP-PD-SNS
```

## Step 3: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn
```

## Step 4: Open the Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
Data_Visualization_Using_NP_PD_SNS.ipynb
```

Run the notebook cells from top to bottom.

---

# ⭐ Project Purpose

This project was completed as part of my **Data Analytics learning journey** to strengthen my practical understanding of Python-based data analysis and visualization.

It demonstrates how raw data can be explored, cleaned, analyzed, and transformed into meaningful visual representations using Python.

---

## 📌 Conclusion

The **Taxi Data Analysis & Visualization** project demonstrates a complete exploratory data analysis workflow using Python.

Starting from dataset loading and missing-value handling, the project progresses through data transformation, statistical exploration, and multiple visualization techniques. These visualizations provide different perspectives of taxi trip characteristics such as **fare, distance, tips, payment methods, pickup boroughs, and relationships between numerical variables**.

This project helped build practical knowledge of **Pandas, NumPy, Matplotlib, Seaborn, Exploratory Data Analysis (EDA), and data visualization**, which are important foundations for a career in Data Analytics.

---

## 👩‍💻 Author

Priyadharshini Naresh D  | Aspiring AI-Driven Data Analyst





   
        
