# Data Acquisition and Data Profiling using Power BI

## Aim

To acquire data from multiple sources and perform data profiling using **Microsoft Power BI** to assess data quality, understand data structure, identify anomalies, and prepare data for further analytical processing.

## Tools / Software Required

- Microsoft Power BI Desktop
- Sales_Data.csv
- Employee_DB.xlsx
- Sample SQL Database

## Theory

### Business Intelligence (BI)

Business Intelligence refers to the technologies, processes, and practices used to collect, integrate, analyse, and present business information. BI transforms raw data into meaningful insights that support better decision-making.

### Data Acquisition

Data Acquisition is the process of collecting and importing data from different sources into a unified environment for processing.

In Power BI, data can be acquired using the **Get Data** option from sources such as:

- CSV files
- Excel files
- SQL databases
- Cloud sources
- Web-based sources

### Data Profiling

Data Profiling is the process of examining a dataset to understand its structure, content, and quality. It helps identify missing values, duplicates, errors, and unusual data.

Important data quality dimensions include:

- **Completeness** – Identifies missing or null values.
- **Uniqueness** – Helps detect duplicate values or records.
- **Validity** – Checks whether values follow expected formats or rules.
- **Consistency** – Checks whether data is uniform across datasets.
- **Accuracy** – Determines whether values correctly represent real-world information.
- **Timeliness** – Checks whether the data is up to date.

## Data Profiling in Power Query

Power BI provides data profiling features through the **Power Query Editor**.

### Column Quality

Shows the percentage of:

- Valid values
- Errors
- Empty values

### Column Distribution

Displays the distribution of values in a column and provides information about:

- Distinct values
- Unique values
- Value frequency

### Column Profile

Provides detailed statistics for a selected column, such as:

- Minimum
- Maximum
- Mean
- Median
- Standard deviation
- Value distribution

## Procedure

1. Open **Microsoft Power BI Desktop**.
2. Select **Get Data**.
3. Import data from CSV, Excel, and SQL database sources.
4. Open the **Power Query Editor**.
5. Select the required table or column.
6. Go to the **View** tab.
7. Enable:
   - Column Quality
   - Column Distribution
   - Column Profile
8. Analyse the profiling information.
9. Identify missing values, errors, duplicates, and unusual values.
10. Clean and prepare the data for further analysis.

## Output

The data profiling results were displayed in Power Query using **Column Quality, Column Distribution, and Column Profile**.

### Screenshots

Add your experiment screenshots below this section.

![Power BI Data Profiling](screenshots/data-profiling.png)
