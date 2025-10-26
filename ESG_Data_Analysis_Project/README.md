# ESG Data Analysis Project
[![Data Velho Rishi](https://img.shields.io/badge/Data%20Velho-Rishi-blueviolet)](https://rishi-analytics.github.io/)
![Project Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Python](https://img.shields.io/badge/Python-3.12-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-purple)
![ESG](https://img.shields.io/badge/Domain-ESG-green)

---

## Overview
This project is built to integrate ESG knowledge with practical analytics. I designed this ESG Data Analysis Project after completing all six courses of the Coursera ‘ESG for All’ Specialization. The project reflects my ability to apply ESG principles to real-world data, highlighting both my analytical skills and my strategic approach to sustainability insights.

This project analyzes a **(Kaggle ESG dataset)[https://www.kaggle.com/datasets/pritish509/s-and-p-500-esg-risk-ratings]** to examine S&P top 100 companies' ESG performance.

It demonstrates **data cleaning, imputation, exploratory data analysis (EDA), and visualization**, linking findings to ESG principles learned in the *“ESG for All”* Coursera Specialization.

---

## Project Objectives:
1. **Examine overall ESG risk profiles**  
2. **Identify top and bottom ESG performers**  
3. **Compare ESG dimension scores (E, S, G) across sectors**  

---

## Dataset
- Contains 503 companies with ESG metrics, sector, industry, employee count, and controversy levels.  
- Key variables: `Total ESG Risk Score`, `Environment Risk Score`, `Social Risk Score`, `Governance Risk Score`, `Controversy Level`, `Full Time Employees`, `Description`.

---

## Analysis Steps
1. **Data Loading & Cleaning**
   - Imported libraries, explored dataset head and info
   - Imputed missing values (mean for numerical, mode for categorical)
   - Checked distributions and outliers

2. **Exploratory Data Analysis (EDA)**
   - Visualized **Total ESG Risk Score** (Histogram, Boxplot, Violin)  
   - Pie chart for **Controversy Level** distribution  
   - **Word cloud** for company descriptions (common terms)  
   - Identified **Top and Bottom ESG performers**  

3. **Sector-wise ESG Analysis**
   - Grouped companies by sector  
   - Calculated average **Environment, Social, Governance** scores  
   - Plotted **dimension-wise comparison across sectors**  
   - Analyzed **average employee count** per sector to highlight social factor influence  

---


## Key Insights
- Most companies have **moderate ESG risk**; few are high-risk outliers  
- Top performers: tech, real estate, services (lowest risk)  
- Bottom performers: energy and industrial sectors (highest risk)  
- **Environmental risk**: highest in Energy & Utilities  
- **Social risk**: varies across sectors; larger workforces indicate potential impact of social initiatives  
- **Governance risk**: relatively stable across sectors  

---
## Visuals: Some images from the project:

### Distribution of Total ESG Risk Scores
<img id="picture1" src="Project_Images/Distribution of Total ESG Risk Score.png" alt="alt text" width="600"/>

---
### Top and Bottom ESG Performers
<img id="picture2" src="Project_Images/ESG Risk Score- Lowest+highest.png" alt="alt text" width="600"/>

---


### Controversy Level Distribution

<img id="picture3" src="Project_Images/Controversy_Level.pie.png" alt="alt text" width="600"/>

---

### Average ESG Dimension Scores by Sector

<img id="picture2" src="Project_Images/Average ESG Dimension Scores by Sector.png" alt="alt text" width="600"/>

---

