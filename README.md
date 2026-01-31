International Debt Analysis – World Bank Data
Project Overview

This project analyzes international debt data collected by the World Bank to understand how debt is distributed across developing countries. Using SQL, the analysis identifies countries with the highest overall debt and the lowest principal repayments, highlighting global debt patterns.

Dataset

The dataset contains country-level debt information measured in USD across multiple debt indicators. Key fields include:

Country name

Indicator name and indicator code

Debt values

The analysis works directly on the provided table without modifying or creating additional datasets.

Key Questions Answered

How many distinct countries are present in the database?

Which country has the highest total debt?

Which country has the lowest amount of principal repayments, based on the indicator code DT.AMT.DLXF.CD?

Analysis Approach

Using SQL, the project applies:

COUNT(DISTINCT ...) to identify the total number of unique countries

Aggregation with SUM() to calculate total debt by country

Filtering by indicator codes to isolate principal repayments

Sorting and limiting results to identify extreme values

Output DataFrames

The final analysis produces three outputs:

num_distinct_countries – total number of unique countries

highest_debt_country – country with the highest total debt

lowest_principal_repayment – country with the lowest principal repayment amount

Tools & Technologies

SQL

PostgreSQL

Key Insight

Global debt data reveals significant variation between countries, with a small number of nations carrying disproportionately high debt burdens, while others contribute minimal principal repayments.

Learning Outcome

This project demonstrates how SQL can be used to explore real-world economic datasets, apply aggregation and filtering techniques, and extract meaningful insights from international financial data.
