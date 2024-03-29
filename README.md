# Exploratory-Data-Analysis

Exploratory Data Analysis - Ames House Price Data set
The dataset describes the sale of individual residential property from 2006 to 2010 in Ames (a small town in Iowa, USA). It was compiled by Dean De Cock who wrote a paper on this (which you should read). More details of this dataset are described in the paper: Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester Regression Project.

This project will require us to read in the data, perform any pre-processing required on the data, and utilize the Python Data Science Software Ecosystem to undertake an Exploratory Data Analysis of the House prices detailing and appropriately documenting any information you can extract from the data. 

# About Dataset:
The data collection comprises information from the Ames Assessor's Office that was utilized in calculating assessed values for individual residential properties sold in Ames, Iowa between 2006 and 2010.
There are 82 columns in the dataset, including 23 nominal, 23 ordinal, 14 discrete, and 20 continuous variables.

In this project, we will carry out these steps to meet our requirements.
1. Reading the data
2. Cleaning the data
3. Analysis
4. Skewing
5. Standard Deviation
6. Visualizing
7. Nominal variable boxplot analysis  
8. Correlation

We will find out more about the steps in detail which will give us more broader view to understand the process.

# 1. Reading the Data

Import libraries: Use Python libraries like pandas and NumPy to read and manipulate data.
Load data: Read the Ames dataset into a pandas DataFrame, typically a CSV file.
Examine structure: Use shape, info(), and head() to visualize dimensions, data types, and initial rows.

# 2. Cleaning the Data

Handle missing values: Decide on strategies like imputation or removal for missing data.
Identify and correct errors: Check for inconsistencies, typos, or out-of-range values.
Format data: Ensure appropriate data types and encoding for categorical variables.
3. Analysis

Summary statistics: Use describe() to get distribution characteristics for numerical variables.
Univariate analysis: Explore individual variables using histograms, bar plots, box plots, etc.
Bivariate analysis: Examine relationships between two variables using scatter plots and correlation.

# 4. Skewness

Measure skew: Calculate skewness using skew() to assess distribution symmetry.
Visualize skew: Histograms and box plots reveal skewness visually.
Consider transformations: Address highly skewed data with transformations like log or square root.

# 5. Standard Deviation

Calculate spread: Use std() to measure the variability of numerical variables.
Interpret standard deviation: Understand how far values typically deviate from the mean.

# 6. Visualizing

Create visualizations: Use libraries like Matplotlib or Seaborn to create informative plots.
Histograms: Show the distribution of numerical variables.
Box plots: Summarize distribution and identify outliers.
Scatter plots: Reveal relationships between two numerical variables.
Bar plots: Visualize categorical variables.

# 7. Nominal Variable Boxplot Analysis

Box plots for categories: Compare distributions of the target variable (e.g., sale price) across categories of a nominal variable.
Identify patterns: Observe differences in medians, quartiles, and outliers among categories.

# 8. Correlation

Measure correlation: Use corr() to calculate correlation coefficients between numerical variables.
Interpret correlation: Understand the strength and direction of linear relationships.
Visualize correlation: Heatmaps effectively display correlation matrices.
