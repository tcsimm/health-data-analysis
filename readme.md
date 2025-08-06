Health Data Analysis: NHIS Adult Summary Statistics

This project explores adult health outcomes across demographics in the United States using data from the National Health Interview Survey (NHIS). It includes data cleaning, exploratory data analysis (EDA), interactive dashboards, and structured SQL queries to uncover trends by year, sex, age group, and health indicators.

---

Project Structure
health-data-analysis/
-  data/ # Raw and cleaned datasets (CSV) 
- dashboards/ # Tableau dashboard PNGs and workbook
- notebooks/ # Jupyter Notebooks for cleaning, EDA, SQL 
- visualizations/ # PNGs of Python-generated charts
- readme.md
- .gitignore
- health.db # SQLite database (created via sql_queries notebook)

## Key Features

- **Data Cleaning:** Standardized column names, parsed confidence intervals, removed duplicates and invalid values
- **EDA in Python:** Histograms, boxplots, and time trends using Pandas, Seaborn, and Matplotlib
- **Insights by Demographics:** Grouped comparisons by age, sex, and year to uncover disparities
- **SQL Queries:** Structured queries using SQLite for reproducible, queryable insights
- **Tableau Dashboard:** Visual summary of outcome trends by year and group

## Technologies Used

- **Python**: `pandas`, `seaborn`, `matplotlib`, `sqlite3`
- **SQLite**: Querying structured data
- **Jupyter Notebooks**: Workflow and documentation
- **Tableau Public**: Interactive data dashboard
- **Git & GitHub**: Version control and collaboration

## Analytical Questions

- How have key health indicators like coronary heart disease and diabetes changed from 2019–2024?
- Which demographic groups report the highest percentage of mental health conditions?
- What were the most common outcomes reported in 2023?
- Are there measurable differences in outcomes between males and females?

## Data Source

- [National Health Interview Survey (NHIS)](https://www.cdc.gov/nchs/nhis/index.htm)
