# Augsburg Meal Plans & Housing Visualization

An analysis of Augsburg University meal plan pricing and housing rates from 2013 to 2025, built with R and published as a Quarto report.

## What it looks at

Meal plan costs have risen 35-42% since 2013 depending on the plan. This project puts that growth next to two things you would expect to drive it: food inflation and on-campus housing rates. The short version is that the correlation is not really there.

## Charts

- **Housing rates**: Percentage of entering freshmen vs. non-freshmen living on campus over time (both groups dropped ~58%)
- **Meal plan costs vs. food inflation**: Side-by-side bar chart with a secondary axis overlaying average food inflation by year

## Stack

- R
- ggplot2
- Quarto
- readxl, tidyverse, scales

## Data

Collected manually from the Augsburg University website. Historical years were recovered using the Wayback Machine, since the site only keeps the current year's data.

## Running it

Open the `.qmd` file in RStudio and render it, or run:
```bash
quarto render auggiemealplans.qmd
```

You will need the `AugsburgMealPlans.xlsx` file in the same directory.
