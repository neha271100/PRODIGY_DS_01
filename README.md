# PRODIGY_DS_01
# Task 01: Data Visualization - Population Distribution
## Overview
This project focuses on visualizing the distribution of population data using bar charts and histograms. The task involves creating visualizations to understand the distribution of various demographic and economic metrics across different states in the United States and countries worldwide.

### Task Details
#### Objective:
Create a bar chart or histogram to visualize the distribution of a categorical or continuous variable, such as the distribution of ages or genders in a population.

#### Sample Dataset:
The dataset used for this task is sourced from the World Bank: World Bank Population Data.

## Dataset Information
### 1. US Census Data
- Source: us_census_.csv.zip
- Description: Contains demographic data for various states in the United States, including total population, gender distribution, racial composition, and employment metrics.
#### Key Columns:
- State: The state name.
-TotalPop: Total population in the state.
- Men: Male population in the state.
- Women: Female population in the state.
- Hispanic, White, Black, Native: Racial composition in percentages.
- PrivateWork, PublicWork, SelfEmployed, FamilyWork, Unemployment: Employment metrics.
### 2. World Population Data
- Source: API_SP.POP.TOTL_DS2_en_csv_v2_3401680.zip
- Description: Contains population data for various countries, including total population by year, country metadata, and economic indicators.
#### Key Columns:
- Country Name: The name of the country.
- Country Code: The code for the country.
- 2020, 2021: Population data for the years 2020 and 2021.
- Land Area: The land area of the country (randomly generated for visualization purposes).
- GDP (2020), GDP per Capita (2020): Economic indicators (randomly generated for visualization purposes).
## Visualizations
### 1. US Census Data Visualizations
- Bar Chart: Total population for selected states.
- Comparison Bar Chart: Comparison of selected metrics (Total Population, Men, Women, Hispanic, White) across selected states.
- Employment Metrics Bar Chart: Comparison of employment metrics across selected states.
- Histograms:
Distribution of total population.
Gender distribution (Men vs. Women).
Average racial distribution (White, Black, Hispanic, Native).
Average employment distribution (PrivateWork, PublicWork, SelfEmployed, FamilyWork).
### 2. World Population Data Visualizations
- Horizontal Bar Chart: Population of countries in 2020.
- Bar Chart: Population of selected countries in 2020.
- Histograms:
Distribution of population in 2020 and 2021.
Population growth (2020-2021).
Population density in 2020.
GDP per Capita in 2020.
Population growth percentage (2020-2021).
## Libraries Used
- pandas for data manipulation.
- matplotlib and seaborn for data visualization.
- zipfile and os for file handling.
## Acknowledgments
- World Bank: For providing the population dataset.
- US Census Bureau: For providing the US Census data.
