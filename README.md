# 🎬 Netflix Movies & TV Shows Data Analysis  

## Overview  
This project focuses on performing Exploratory Data Analysis (EDA) on a dataset of Netflix movies and TV shows to uncover trends, patterns, and actionable insights.  
The goal is to transform raw data into meaningful information that can support content strategy and business decision-making.

---

## Dataset Information  
- Total records: 9,800+ titles  
- Expanded dataset: 25,000+ records (after genre transformation)  

### Key Features:
- Title  
- Release Year  
- Genre  
- Popularity  
- Vote Count  
- Vote Average  

---

## 🧹 Data Preprocessing  
The dataset was cleaned and transformed to ensure accurate analysis:

- Converted release dates into year format  
- Removed irrelevant columns (overview, language, poster URL)  
- Handled multi-genre columns by splitting and exploding them  
- Categorized vote averages into meaningful groups:
  - Not Popular  
  - Below Average  
  - Average  
  - Popular  
- Optimized data types for efficient processing  

---

## Analysis & Visualizations  
Performed detailed EDA using Python libraries:

- Genre distribution analysis  
- Popularity trends across categories  
- Vote distribution and engagement patterns  
- Release year trends  
- Identification of top and low-performing content  

Visualization tools used:
- Matplotlib  
- Seaborn  

---

## Key Insights  
- Drama is the most dominant genre (~14% of content)  
- Around 25% of titles fall into the "popular" category  
- 2020 recorded the highest number of releases, indicating peak production  
- Popularity varies significantly across genres  
- Some titles perform strongly across multiple genres, indicating cross-category appeal  

---

## Tech Stack
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---

## Skills Demonstrated  
- Exploratory Data Analysis (EDA)  
- Data Cleaning & Transformation  
- Feature Engineering  
- Data Visualization  
- Analytical Thinking  
- Insight Generation  

---

## How to Run  

1. Install dependencies:
pip install pandas numpy matplotlib seaborn  

2. Open Jupyter Notebook:
jupyter notebook  

3. Run all cells to reproduce the analysis  

---

## Conclusion  
This project demonstrates how raw data can be transformed into actionable insights.  
It highlights the importance of data-driven decision-making in understanding content trends and user preferences.

---

## Future Improvements  
- Build an interactive dashboard (Power BI / Tableau)  
- Add predictive modeling for content success  
- Perform deeper genre-based analysis  
