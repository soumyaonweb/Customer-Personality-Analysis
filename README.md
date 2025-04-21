This repository focuses on the cleaning and preparation of the Customer Personality Analysis dataset, which aims to help businesses understand their customer segments better and improve targeted marketing efforts.

Dataset Overview:
The dataset is sourced from Kaggle and contains demographic and behavioral attributes for customers, including:

Personal information (e.g. age, education, marital status)
Product purchases
Campaign responses
Web and store interaction metrics

Cleaning & Preprocessing Steps
Using Python and Pandas, the following steps were performed:

1. Remove Duplicates
Duplicate rows were dropped to ensure data integrity.
2. Handle Missing Values
Rows containing NaN values were removed for simplicity.
3. Standardize Column Names
All column names were converted to lowercase with underscores.
4. Convert Date Formats
The Dt_Customer column was parsed into a standard datetime format.
Dataset Summary After Cleaning:
Rows: 2,216
Columns: 29
Missing Values: 0
Date Columns: Converted to datetime
Standardized Columns: Yes
