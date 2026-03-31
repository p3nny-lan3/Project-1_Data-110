# Project 1, Data-110

This project explores a dataset describing socioeconomic characteristics and impacts by Maryland Senate Districts using visualization techniques. From this dataset, I analyze the question of: From 2019-2023, how does median household income and the percentage of families in poverty affect the rental burden across all 47 Maryland Senate Districts?

## Dataset
The data comes from the American Community Survey 5-year Estimates (2019-2023) which are U.S. Census Bureau surveys that documents the average characteristics concerning housing and population metrics recorded during the 2019 to 2023.

## What I Did:
- Data cleaning: Standardized column headers by converting to lowercase and replacing spaces, dashes, and periods with underscores for better readability.
- Feature Engineering: Scaled Median Income by 1,000 to create an income_thousands variable, improving the readability of income.
- Categorical Binning: Grouped all 47 Senate Districts into 10 geographic regions using case_when().
- Statistical Analysis: Performed a Multiple Linear Regression to model the relationship between income, poverty, and rent burden, followed by a Residual Analysis using diagnostic plots.
  
## Tools Used
- R packages: library(tidyverse), library(ggplot2), library(dplyr), library(plotly)
- R Studio
- This website to retrieve color hex codes
  
## Author
Rin Hwang
