# Python DA Assignment 1: Data Analysis using NumPy and Pandas

This assignment practices basic data analysis with NumPy and Pandas. It uses daily temperatures, student marks, and sales transaction records to demonstrate how to organize, inspect, select, summarize, and update data.

## Assignment overview

### NumPy temperature analysis

The first part creates an array containing the average temperatures for seven days. It explores the array's dimensions, numeric type, and number of values. The temperatures are converted from Celsius to Fahrenheit, and the weekly maximum, minimum, and average are identified. Slicing is used to view the first three days, the final two days (the weekend), and the middle three days.

A second array organizes temperature readings for two weeks. Each row represents one week, and each column represents a day of the week. The exercise checks the array's overall dimensions and number of values, views each week separately, and selects the weekend readings from both rows.

### Pandas Series of student marks

The Series section records five marks using rank names as labels. It demonstrates retrieving a value by its position and selecting values by their labels. A condition is used to find ranks with marks above 90. The first rank's mark is then raised to 100, the last rank is removed, and the remaining marks are converted to CGPA by dividing each by 10.

### Pandas transaction DataFrame

The DataFrame section organizes ten transactions by ID, product category, region, and amount. It explores the first and last rows, the table's dimensions, column names, and data types. It then focuses on selected columns and the last three columns, filters for North region transactions above 200, counts product categories, lists the regions, and calculates the mean transaction amount for each region.

The final steps update the amount for transaction 102 to 165, calculate a temporary discount equal to 10% of each amount, remove transaction 109, and delete the temporary discount column. The resulting table has nine rows and retains the updated amount for transaction 102.

## Solution notebook

The companion notebook, `Python_DA_Assignment_1_Step_by_Step_Solution.ipynb`, contains the full worked solution with runnable cells and explanations. Open it in Jupyter Notebook, JupyterLab, or Google Colab and run the cells in order. It requires Python, NumPy, and pandas.
