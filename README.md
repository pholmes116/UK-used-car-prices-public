# Exploring Factors Influencing UK Used-Car Prices

## Authors

Imar Colic, Peter Holmes, Finbar Rhodes

## Overview

This project, completed as part of LSE's ST445 Managing and Visualising Data course, investigates the factors that shape the UK used-car market with a focus on Volkswagen Golf pricing. While framed around a hypothetical narrative of helping a friend estimate a resale value, the analysis more broadly examines:
- UK market trends and their relationship to economic indicators (inflation, unemployment).
- Car-specific attributes such as mileage, transmission, fuel type, and engine size.
- Environmental factors for VW Golf models, including CO2 emissions.

Using datasets from the UK Office of National Statistics, a Kaggle-sourced sample of 100k used cars, and VW emissions data, we applied data cleaning, reshaping, and exploratory visualization techniques to uncover patterns. A linear regression model then demonstrated how these factors can be combined to estimate vehicle prices.

## Project Structure

.\
├── Car CSVs/\
├── ONS CPIH indices/\
├── VW Golf Emissions/\
├── UK_car_rental.ipynb\
└── README.md

Car CSVs contain the Kaggle-sourced used-car datasets, ONS CPIH indices contain economic indicators from UK ONS, VW Golf Emissions contain CO2 emission data for VW Golf models.

## Methods

- **Data acquisition & cleaning**: ONS statistics, Kaggle car data, VW reports
- **Wrangling**: merging datasets, feature engineering (e.g., age, efficiency)
- **Visualization**: time-series trends, correlations, comparative plots
- **Modeling**: Linear regression on VW Golf data to estimate price impact

## Findings

- Market-wide used-car pricing correlates with UK economic indicators
- Mileage, transmission, engine size, and fuel type are the strongest car-level predictors
- VW Golf pricing is also influenced by environmental characteristics such as CO2 emissions
- Regression modeling illustrates how these factors combine to yield realistic value estimates

## Contact

For questions or contributions, reach out via GitHub Issues or email pholmes116@gmail.com.
