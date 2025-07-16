# SQL- Based Analysis
This project integrates web scraping, database creation, and SQL-based data exploration focusing on economic data from the International Monetary Fund (IMF) World Economic Outlook database.

## About the data
The dataset used contains the Gross Domestic Product (GDP) at current prices, measured in billions of U.S. dollars, for a selection of countries over a five-year period (2020–2025).
- Source: IMF World Economic Outlook database
- Time frame: Annual GDP data from 2020 to 2025
- Countries covered: Bangladesh, Bhutan, Brunei Darussalam, Cambodia, China, and others from South Asia and the surrounding region
- Structure:
  Each row represents a country
  Columns contain GDP figures for each year

## About the Project
This project shows the end-to-end process of working with real-world macroeconomic data:
1. Web scraping - Use Python to scrape GDP data from the IMF.
2. Database creation - Store the cleaned GDP data in a local SQLite database.
3. SQL-based analysis - Perform a series of SQL queries to extract insights using WHERE, GROUP BY, ORDER BY, Aggregate functions like AVG, SUM, COUNT etc.
