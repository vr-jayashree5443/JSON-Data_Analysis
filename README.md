# JSON_Technology_Dataset_-Data_Analysis

# Project: JSON Data Analysis

## Overview
This project focuses on analyzing JSON data retrieved from a dataset containing information about books. The analysis involves data exploration, cleaning, manipulation, and visualization using Python and various libraries like Pandas, Matplotlib, and Seaborn.

## Project Structure
The project is organized into several steps:

1. **Converting JSON to DataFrame**: Convert the JSON data into a Pandas DataFrame for analysis.
   
2. **Data Exploration**: Explore the dataset to understand its structure, statistical information, and identify any issues such as missing values or duplicates.
   
3. **Data Cleaning**: Clean the dataset by addressing issues like missing values, data types, duplicate records, and inconsistencies.
   
4. **Data Analysis**: Analyze the cleaned dataset to gain insights and answer specific questions about the data.
   
5. **Visualization**: Visualize the analyzed data using graphs and charts to communicate findings effectively.

## Steps Involved

1. **Converting JSON to DataFrame**: Use Pandas to read the JSON data and convert it into a DataFrame.

2. **Data Exploration**: Explore the dataset by printing column names, checking column data types, statistical information, and identifying any missing values.

3. **Data Cleaning**:
    - Clean the ISBN column by removing non-numeric characters.
    - Handle missing values in the ISBN column.
    - Show full column values without truncation.
    - Identify and handle duplicated rows based on specific columns.
    - Reconstruct IDs to ensure continuity.
    - Convert the 'pageCount' column to integer and fill missing values with the mean.
    - Extract the year from the 'publishedDate' column and fill missing values with the mean year.
    - Remove unnecessary columns like 'thumbnailUrl', 'shortDescription', and 'longDescription'.
    - Handle missing values and inconsistencies in the 'publishedYear' column.
    - Remove the '_id', 'authors', and 'categories' columns.

4. **Data Analysis**:
    - Plot the counts of different categories in the 'status' column.
    - Plot the counts of books published in different years.
    - Plot the counts of books published in different time ranges (e.g., 1600-1700, 1700-1800, etc.).
    - Identify the book with the highest number of pages.
    - Plot a graph of the first 10 rows, with book titles on the x-axis and the number of pages on the y-axis.

5. **Conclusion**: Summarize the key findings and insights obtained from the analysis.

## Libraries Used
- Pandas: For data manipulation and analysis.
- Matplotlib & Seaborn: For data visualization.

## Getting Started
To run the project, you need:
- Python installed on your machine.
- Jupyter Notebook or any other Python IDE.
- Install required libraries using pip:
  ```
  pip install pandas matplotlib seaborn
  ```

## Usage
- Clone the repository or download the project files.
- Open the Jupyter Notebook file (Project-3 (JSON).ipynb) in your preferred environment.
- Execute the cells sequentially to perform data analysis and visualize the results.

---
