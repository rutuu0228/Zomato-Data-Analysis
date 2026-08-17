# 🍽️ Zomato Data Analysis — Python EDA Project

<p align="center">
  <b>Exploratory Data Analysis of Zomato Restaurant Data using Python</b><br>
  <i>Turning restaurant data into clear, business-focused insights 📊</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-EDA-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-Analysis-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-Visualization-4C8CBF?style=for-the-badge" alt="Seaborn">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
</p>

---

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Zomato restaurant dataset using Python. It explores restaurant categories, customer voting patterns, ratings, online/offline ordering behavior, and approximate customer spending.

The project follows a practical analyst workflow: **understand → clean → analyze → visualize → answer business questions → communicate insights**.

## 🎯 Business Questions

1. 🍴 Which restaurant type has the largest presence in the dataset?
2. 🗳️ Which restaurant type receives the most customer votes?
3. ⭐ What rating range is most common?
4. 💰 What is the average cost for two people?
5. 📱 Which ordering mode has the higher average rating?
6. 🏪 Which restaurant type has the strongest offline-order presence?

## 🧰 Tech Stack

| Tool | Purpose |
|---|---|
| **Python** | Core programming and analysis |
| **Pandas** | Data loading, cleaning and manipulation |
| **NumPy** | Numerical operations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualization |
| **Jupyter Notebook** | Interactive analysis and documentation |

## 📂 Repository Structure

```text
Zomato-Data-Analysis/
│
├── 📓 zomato_data_analysis.ipynb             # Original analysis notebook
├── 📓 notebooks/
│   └── zomato_eda_professional.ipynb        # ⭐ Portfolio-ready EDA notebook
├── 📄 Zomato data .csv                       # Dataset
├── 📝 Questions to solve.txt                 # Original business questions
├── 📑 zomato_data_analysis_code pdf.pdf     # PDF code reference
├── 📦 requirements.txt                       # Python dependencies
├── 🚫 .gitignore
└── 📖 README.md
```

> **Recommended:** Start with `notebooks/zomato_eda_professional.ipynb` for the cleaned, structured portfolio version. The original notebook is retained for project history.

## 🔎 Analysis Workflow

```text
Raw Zomato Data
      ↓
Data Loading
      ↓
Data Understanding
      ↓
Data Cleaning & Type Conversion
      ↓
Exploratory Data Analysis
      ↓
Visualization
      ↓
Business Questions
      ↓
Insights & Business Takeaways
```

## 📊 Dataset Snapshot

The dataset contains **148 restaurant records and 7 columns**, including restaurant name, online ordering, table booking, rating, customer votes, approximate cost for two people, and restaurant type.

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/rutuu0228/Zomato-Data-Analysis.git
cd Zomato-Data-Analysis
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Then open:

```text
notebooks/zomato_eda_professional.ipynb
```

## 🧹 Data Preparation

The professional notebook includes reproducible preparation steps such as:

- Standardizing column names
- Converting restaurant ratings from text such as `4.1/5` into numeric values
- Checking missing values
- Checking duplicate rows
- Keeping analysis logic reproducible instead of hard-coding results

## 📈 What the Analysis Demonstrates

- Data loading with Pandas
- DataFrame inspection and understanding
- Data cleaning and type conversion
- Grouping and aggregation
- Categorical analysis
- Customer engagement analysis using votes
- Rating distribution analysis
- Online vs. offline comparison
- Restaurant-type comparison
- Data visualization with Matplotlib and Seaborn
- Business-oriented interpretation

## 💼 Portfolio Value

This project demonstrates the core workflow expected from an entry-level **Data Analyst / Data Science** candidate: starting with a raw dataset, identifying meaningful questions, cleaning the data, exploring patterns, visualizing evidence, and translating results into business takeaways.

It intentionally focuses on **EDA and analytics fundamentals**, rather than adding unnecessary machine learning.

## 🔗 Project Files

- ⭐ [Portfolio EDA Notebook](./notebooks/zomato_eda_professional.ipynb)
- 📓 [Original Notebook](./zomato_data_analysis.ipynb)
- 📊 [Dataset](./Zomato%20data%20.csv)
- 📝 [Business Questions](./Questions%20to%20solve.txt)
- 📑 [Code PDF](./zomato_data_analysis_code%20pdf.pdf)

## 👨‍💻 Author

**Rutuu** — B.Sc. Data Science Student

Focused on **Data Science • Data Analytics • Python • SQL • Machine Learning • AI**.

⭐ If you find this project useful, consider starring the repository!

---

<p align="center"><b>Built with Python 🐍 • Analyzed with Pandas 📊 • Visualized with Matplotlib & Seaborn 📈</b></p>
