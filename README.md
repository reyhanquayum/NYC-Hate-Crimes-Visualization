[View the Full PDF Report Here](./NYC%20Hate%20Crimes%20Visualiztion.pdf)

# NYC Hate Crimes Visualization

## Overview

This project analyzes hate crime incidents in New York City to identify which demographic groups (e.g., race, religion, sexual orientation) have been most frequently targeted. It uses publicly available data from the NYPD and NYC Open Data to provide statistical analysis and visualizations.

- **Author**: Reyhan Quayum  
- **Date Completed**: February 14, 2023  
- **Focus**: Criminology, Data Analysis  
- **Location**: New York City  
- **Time Frame**: October 2020 – February 2023  

---

## Project Structure

```
NYC-Hate-Crimes-Visualization/
├── .gitignore
├── NYC Hate Crimes Visualiztion.pdf # Project report
├── data/
│ └── raw/
│ ├── adult19.csv # Bonus dataset (height vs weight)
│ ├── example-data.csv # Sample CSV
│ └── NYPD_Hate_Crimes.csv # Main dataset
├── src/
│ └── NYC Hate Crimes Visualiztion.ipynb # Jupyter notebook with code and analysis
```

---

## Dataset

**Primary Source**: [NYPD Hate Crimes Dataset](https://data.cityofnewyork.us/d/bqiq-cu78)  
- **Records**: 1,971  
- **Fields of Interest**:
  - Bias Motivation
  - Occurrence Year
  - Borough
  - Offense Category
  - Victim Demographics  
- **Last Accessed**: February 14, 2023  
- **License**: To be confirmed  

---

## Key Analysis

- **Most targeted group**: Jewish community (`ANTI-JEWISH`)
- **Peak location/time**: Brooklyn South, 2019
- **Bias frequency ranking**:
  1. ANTI-JEWISH
  2. ANTI-ASIAN
  3. ANTI-MALE HOMOSEXUAL (GAY)

---

## Report

You can view the final report as a PDF here:

[View the PDF Report](./NYC%20Hate%20Crimes%20Visualiztion.pdf)

This PDF is generated from the Jupyter notebook and contains all analysis, visualizations, and conclusions.


---

## Visualizations

- Bar chart showing top 5 bias motives.
- Scatter plot showing correlation between height and weight (bonus).

![Top 5 Bias Motives](/img/plot.png)

---

## Bonus: Height vs. Weight Correlation

Using the `adult19.csv` dataset:
- **Pearson correlation coefficient**: ~0.76
- Strong positive correlation between height and weight.

![Height-Weight Correlation](/img/plot2.png)

---

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `matplotlib`
  - `csv`
  - `statistics`

