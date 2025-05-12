# 📺 Netflix Data Analysis Project

Welcome to the Netflix Data Analysis Notebook!  
This project focuses on performing exploratory data analysis (EDA) on a Netflix dataset to extract insights about the content available on the platform.

## 📌 Objective
The goal is to analyze trends in Netflix's catalog such as:
- Distribution of content by type (Movies vs. TV Shows)
- Year-wise content additions
- Top contributing countries
- Common genres and keyword analysis
- Duration and rating patterns

## 🛠 Tools & Libraries Used
- **Python**
- **Pandas** – for data manipulation  
- **NumPy** – for numerical operations  
- **Matplotlib & Seaborn** – for data visualization  
- **Missingno** – for visualizing missing data  
- **WordCloud** – for genre/tag analysis

## 📊 Key Insights
- Identified the years with the highest content additions
- Analyzed genre distributions using `explode()` to flatten multi-valued fields
- Visualized top countries contributing content to Netflix
- Explored content ratings and durations across categories

## 📂 Dataset
The dataset was sourced from Kaggle and contains metadata about Netflix titles including:
- Title, Type, Director, Cast, Country
- Date Added, Release Year, Rating, Duration
- Genre (Listed_in), Description

## 📎 Project Highlights
- Used `explode()` to handle multiple genres per title
- Cleaned and handled null values effectively
- Generated visual summaries using Seaborn and Matplotlib
- Created a word cloud of popular keywords from descriptions

---


