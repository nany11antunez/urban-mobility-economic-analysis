# urban-mobility-economic-analysis

 **American Development Bank Economic Analysis**

This repository contains an exploratory analysis of the relationship between urban mobility, traffic congestion, and economic productivity across major cities.

The project integrates mobility and socioeconomic data to examine traffic delays, travel times, GDP per capita, population, and air pollution, identifying patterns and outliers that may be relevant to urban infrastructure and sustainable transport planning.

## 📂 Repository Contents
The analysis can be viewed directly on GitHub or run in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wws8erbdlWriSjSDVlcmHqo7JnYUeBHG#scrollTo=7a3bdb8e)

urban_mobility_economic_analysis.ipynb → Main notebook containing data cleaning, data integration, exploratory data analysis (EDA), visualisations, outlier analysis, and business insights.

## 🧠 Analysis Objective

The objective of this analysis was to investigate the relationship between urban mobility and economic productivity across major cities worldwide.

The analysis focused on:

- Traffic congestion and total time lost due to delays.
- Real-time travel times across cities.
- GDP per capita as an indicator of economic productivity.
- Population size as a potential factor influencing congestion.
- PM2.5 levels as an environmental indicator associated with urban mobility.
- Differences in mobility patterns across different economic contexts.

## 🗂️ Data

The analysis combines data from two main sources:

- `TomTom Traffic Index` — Mobility indicators, including traffic delays and real-time travel times.
- `OECD Cities` — Socioeconomic and environmental indicators including GDP per capita, population, and PM2.5.

The original project considered major cities worldwide. After data cleaning, filtering, and integration, the final analytical dataset contains 15 cities across 7 Latin American countries, using data from 2024.

Countries included:
- **Argentina**
- **Brazil**
- **Chile**
- **Colombia**
- **Mexico**
- **Peru**
- **Uruguay**

The final dataset contains cities with matching records available from both sources for the selected year.

## 🔎 Analysis Process

* **Data Cleaning and Standardisation:** Converted dates and numerical variables, standardised column names, and correction of structural inconsistencies between the datasets.
* **Data Filtering:** Extracted the year from traffic records and filtered the analysis to 2024.
* **Data Aggregation:** Aggregated mobility and socioeconomic information at city-year level to create a consistent analytical dataset.
* **Data Integration:** Combined the two sources using an INNER JOIN on city and year, retaining cities with valid records in both datasets.
* **Data Validation and Quality:** Reviewed data types, distributions, missing values, and consistency across the integrated dataset.
* **Exploratory Data Analysis (EDA):** Used histograms, boxplots, and comparative visualisations to examine distributions, relationships, and outliers.
* **Mobility & Economic Analysis:** Compared traffic delays and travel times with GDP per capita and population to identify relevant patterns across cities.
* **Outlier Analysis:** Investigated cities with unusually high or low congestion levels relative to their economic and demographic context.

## 📊 Key Findings

- The analysis did not identify a simple linear relationship between GDP per capita and traffic congestion.
- Population scale and urban demand appears to be important factors in congestion, particularly large cities with low-to-medium GDP per capita.
- Bogotá and Lima presented high traffic delays alongside comparatively lower GDP per capita within the analysed sample.
- Montevideo stood out for combining relatively high GDP per capita with comparatively low traffic congestion. 
- Bogotá recorded a PM2.5 concentration of 17.60 µg/m³, adding an environmental dimension to the analysis of urban mobility challenges.

Overall, the results suggest that congestion cannot be explained by economic productivity alone. Population scale, urban structure, infrastructure, and other local factors may also contribute to differences in mobility outcomes.

## 💡 Business Insights

The analysis provides a basis for:

- Identifying cities where high congestion and lower economic capacity occur simultaneously.
- Evaluating mobility challenges alongside socioeconomic and environmental indicators.
- Supporting further investigation into infrastructure and sustainable transport needs.
- Using population, GDP per capita, traffic delays, and air quality together to provide a broader view of urban mobility challenges.
- Identifying cities that warrant deeper analysis before potential infrastructure interventions are considered.
- The analysis also highlights the value of a multi-year approach. Extending the dataset beyond 2024 could help distinguish persistent structural mobility patterns from temporary or year-specific effects.

## 🛠️ Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

## 📌 Demonstrated Skills

- Data cleaning
- Data integration
- Data validation
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Outlier detection
- Data visualisation
- Socioeconomic data analysis
- Data-driven decision support
- Business insights

