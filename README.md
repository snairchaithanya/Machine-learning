## Machine Learning
This repository contains three Machine Learning tasks focusing on various aspects of data analysis, model training, and evaluation. 
Each task is designed to address different Machine Learning challenges and provide comprehensive solutions.
# Task1. Measures of Descriptive statistics-Central Tendency, spread **
How to measure the central tendency is explained and coded in this task
we are given house_price.csv which contains property prices in the city of Bangalore. we need to examine price per square feet do the following:
Detect the outliers and remove it using:
  1)**Mean Function**
  2) **Percentile method**
  3. **IQR(Inter quartile range method)**
  4.**Normal distribution**
  5.**Zscore method**
Also, plot the box plot(for all the numerical columns), histplot(to check the normality of the column(price per sqft column))
Check the correlation between all the numerical columns and plot heatmap.
Scatter plot between the variables to check the correlation between them.
dataset: https://drive.google.com/file/d/1UlWRYU0UglE2ex3iFse0J6eCLEU8g98P/view


# Task2. Hypothesis testing
Q1.**Suppose a child psychologist claims that the average time working mothers spend talking to their children is at least 11 minutes per day. 
You conduct a random sample of 1000 working mothers and find they spend an average of 11.5 minutes per day talking with their children. Assume prior research suggests the population standard deviation is 2.3 minutes.
Conduct a test with a level of significance of alpha = 0.05.**
Q2.**A coffee shop claims that their average wait time for customers is less than 5 minutes. To test this claim, a sample of 40 customers is taken, and their wait times are recorded. 
The sample mean wait time is found to be 4.6 minutes with a standard deviation of 0.8 minutes. 
Perform a hypothesis test at a significance level of 0.05 and determine whether there is enough evidence to support the coffee shop's claim**


# Task 3. Data Preprocessing
Objective:The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges 
such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning.
Key Components to be fulfilled:
1)**Data Exploration:   Explore the data, list down the unique values in each feature and find its length. Perform the statistical analysis and renaming of the columns.**
2)**Data Cleaning:**
Find the missing and inappropriate values, treat them appropriately. Remove all duplicate rows. Find the outliers.
Replace the value 0 in age as NaN
Treat the null values in all columns using any measures(removing/ replace the values with mean/median/mode)
3)**Data Analysis:**
 Filter the data with age >40 and salary<5000,
Plot the chart with age and salary,
Count the number of people from each place and represent it visually.
4)**Data Encoding:**
Convert categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms.
5)**Feature Scaling:**
After the process of encoding, perform the scaling of the features using standardscaler and minmaxscaler. 
dataset : https://drive.google.com/file/d/1F3lRf32JM8ejnXq-Cbf9y7fa57zSHGz_/view

# Task 4 : Regression
## Problem Description:
A Chinese automobile company aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

1. **Which variables are significant in predicting the price of a car.**
   - Identify the key factors that influence car pricing, such as engine size, mileage, brand, etc.
   
2. **How well those variables describe the price of a car.**
   - Determine the strength and relevance of these factors in accurately predicting the car's price.
  
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.
## Business Goal
You are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for the management to


# Task 5: Classification 
The objective of this assessment is to evaluate your understanding and ability to apply supervised learning techniques to a real-world dataset.
Dataset:
Use the breast cancer dataset available in the sklearn library.
Key components to be fulfilled :
1. Loading and Preprocessing
   - Load the breast cancer dataset from sklearn.
   - Preprocess the data to handle any missing values and perform necessary feature scaling.
   - Explain the preprocessing steps you performed and justify why they are necessary for this dataset.
2. Classification Algorithm Implementation
   - Implement the following five classification algorithms:
     1. **Logistic Regression**
     2. **Decision Tree Classifier**
     3. **Random Forest Classifier**
     4. **Support Vector Machine (SVM)**
     5. **k-Nearest Neighbors (k-NN)**
   - For each algorithm, provide a brief description of how it works and why it might be suitable for this dataset.
3. Model Comparison
   - Compare the performance of the five classification algorithms.
   - Which algorithm performed the best and which one performed the worst.
### Objective:
The goal is to evaluate ability to apply supervised learning techniques to this dataset. This involves:

>Loading and Preprocessing: Preparing the data for analysis.
>Classification Algorithm Implementation: Applying various classification algorithms.
>Model Comparison: Assessing the performance of different algorithms.


