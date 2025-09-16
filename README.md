# Data Analysis Assignment

## Objective
The goal of this project is to **load, explore, analyze, and visualize a dataset** using Python libraries **pandas**, **matplotlib**, and **seaborn**. This assignment demonstrates basic data manipulation, statistical analysis, and visualization techniques.

## Dataset
We are using the **Iris dataset** for this assignment.  
- The dataset contains **150 samples** of Iris flowers.  
- Columns:  
  - `sepal length (cm)`  
  - `sepal width (cm)`  
  - `petal length (cm)`  
  - `petal width (cm)`  
  - `species` (Setosa, Versicolor, Virginica)

The dataset is included in the repository as `dataset.csv`.

## Features Implemented
1. **Data Loading**: Read the CSV file into a Pandas DataFrame.  
2. **Data Exploration**: Inspect the first few rows, column data types, and missing values.  
3. **Data Cleaning**: Handle missing values by filling with column mean (if any).  
4. **Basic Analysis**:
   - Descriptive statistics (`mean`, `median`, `std`, etc.)  
   - Grouping by `species` to compute average petal length  
   - Correlation analysis between numerical columns  
5. **Visualizations**:
   - **Bar Chart**: Average petal length per species  
   - **Histogram**: Distribution of sepal length  
   - **Scatter Plot**: Sepal length vs petal length  
   - **Line Chart**: Average sepal length per species  
6. **Observations & Insights**: Identify patterns and trends in the dataset.

## How to Run
1. **Clone the repository** or download the files:  
   ```bash
   git clone https://github.com/YourUsername/Data_Analysis_Assignment.git
