# Gender Pay Gap by Education Level in Saudi Arabia

## Overview
This project explores average salaries in Saudi Arabia based on degree level and gender, using data from 2017 to 2021. It matters because it highlights how education level affects earning potential in the Saudi labor market — encouraging people to pursue further education to secure higher-paying jobs. The analysis also reveals a persistent gender pay gap across all education levels, which is an important factor for policymakers and employers to consider.

## Dataset
The dataset was sourced from GASTA (General Authority for Statistics) via Kaggle. It contains 504 entries and 6 columns: Degree Level, Nationality, Gender, Year Quarter, Salary, and Currency. The data covers the period from 2017 to 2021, though 2021 includes only 2 quarters instead of 4.

## Approach
The analysis began by loading the dataset using the Pandas library (`pd.read_csv`) and inspecting it with `.info()` and `.describe()`. Salaries were then grouped by degree level and gender to calculate both the absolute and relative gender pay gaps. A yearly trend was also examined to see how the gap changed between 2017 and 2021, accounting for the incomplete 2021 data. Finally, the results were visualized using bar and line charts to highlight patterns across education levels and over time.

## Results
The analysis reveals a persistent gender pay gap across all education levels in Saudi Arabia. In absolute terms, the gap is largest at the Doctorate level (5,325 SAR), where men earn significantly more than women. However, when measured as a percentage, the largest relative gap appears at the Secondary level (60%), while the Diploma level shows the smallest gap overall (both in SAR and percentage). The yearly trend from 2017 to 2020 shows the gap remained relatively stable, ranging between 30% and 33%. A sharp increase to 49.9% appears in 2021, but this should be interpreted with caution since that year's data only includes 2 out of 4 quarters.

## What I'd Improve With More Time
In the future, I would like to analyze how nationality affects the results, in addition to Degree Level and Gender. It would also be interesting to explore what a scenario of equal pay between men and women would look like, and how much of an economic impact that could have.

