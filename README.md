# Economic and Financial Trends Analysis Using Python

## Project Overview

This project analyses monthly aggregate deposits and bank credit of scheduled commercial banks in India from January 2016 to June 2026. The data was obtained from the Reserve Bank of India's Database on Indian Economy (DBIE).

The project uses Python for data cleaning, exploratory data analysis, statistical calculations, and visualization to understand changes in India's banking sector over time.

## Research Question

How have bank credit and aggregate deposits in India changed over time, and what can their growth patterns tell us about the banking sector?

## Objectives

- Examine trends in aggregate deposits and bank credit.
- Compare overall percentage growth and year-on-year growth.
- Analyse changes in the credit-to-deposit ratio.
- Track the gap between aggregate deposits and bank credit.
- Present findings through charts and descriptive analysis.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Key Findings

- Aggregate deposits increased by approximately **187.96%** over the period analysed.
- Bank credit increased by approximately **210.82%**.
- Average year-on-year deposit growth was approximately **10.41%**, while average year-on-year credit growth was approximately **11.46%**.
- The credit-to-deposit ratio increased from approximately **76.54%** in January 2016 to **82.61%** in June 2026.
- The gap between aggregate deposits and bank credit increased from approximately **₹21.63 lakh crore** to **₹46.15 lakh crore**.

## Methodology

1. Loaded the dataset and selected the required variables.
2. Cleaned the data and converted financial values and dates into appropriate formats.
3. Checked for missing values, duplicate months, and missing monthly observations.
4. Calculated descriptive statistics and visualized monthly trends.
5. Calculated overall growth, year-on-year growth, the credit-to-deposit ratio, and the deposit-credit gap.
6. Interpreted the results using charts and summary statistics.

## Limitations

- The analysis is descriptive and does not establish causal relationships.
- Financial values are nominal and have not been adjusted for inflation.
- The dataset represents aggregate banking figures rather than individual banks.
- The credit-to-deposit ratio alone does not provide a complete measure of banking liquidity.

## Data Source

Reserve Bank of India (RBI), Database on Indian Economy (DBIE).

[Access the RBI DBIE dataset](https://dbie.rbihub.in/statistics?table=financial_sector.r803_scheduled_commercial_banks_select_aggregates)

## Future Scope

Further analysis could include inflation-adjusted trends, comparisons across banking categories, additional financial indicators, and forecasting using statistical or machine-learning methods.