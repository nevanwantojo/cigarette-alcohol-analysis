cigarette-alcohol-analysis
Data Science Computer Programming Final Project
This project analyzes patterns of cigarette and alcohol addiction using a dataset of individuals across various countries. It aims to explore addiction levels, compare habits, and examine the potential relationship between income and addiction.

Dataset
File: `addiction_population_data.csv`
The dataset contains individual-level data, including:
- Demographics (age, gender, country, income)
- Addiction habits (`smokes_per_day`, `drinks_per_week`)
- Lifestyle and health attributes

Objectives
Objective 1: Compare Smoking vs Drinking Rates
- Calculated the average number of cigarettes smoked per day and drinks consumed per week.
- Visualized using a bar chart.
 Objective 2: Top 5 Most Addicted Countries
- Grouped data by country and summed total addiction (smoking + drinking).
- Identified and visualized the top 5 countries with the highest addiction.
Objective 3: Analyze Income vs Addiction
- Normalized annual income to allow comparison.
- Created a scatter plot with regression line to observe any correlation between income and total addiction.

Data Preprocessing
- Filled missing values in `smokes_per_day`, `drinks_per_week`, and `annual_income_usd`.
- Created a new column `total_addiction = smokes_per_day + drinks_per_week`.
- Normalized `annual_income_usd` using MinMaxScaler from scikit-learn.

Visualizations
- Bar Chart: Average smoking vs drinking
- Bar Chart: Top 5 countries with highest addiction
- Scatter Plot: Income vs total addiction level

Files Included

- addiction_analysis.ipynb 
- addiction_population_data.csv
- Cigarettes and Alcohol Addiction report- data science final project

How to Run
1. Clone this repo or download the notebook and CSV file.
2. Open "addiction_analysis.ipynb" in Jupyter Notebook.
3. Run all cells to reproduce the analysis and plots.

These insights can be useful for health researchers, educators, and policy makers.

Author

Final project for the NTNU DSCP Course, 2025  
41347050s陳志誠 41347050s@gapps.ntnu.edu.tw                                                            
41384246i鄭永勝 41384246i@ntnu.edu.tw                                                                        
41384238i吳素芬 41384238i@gapps.ntnu.edu.tw
