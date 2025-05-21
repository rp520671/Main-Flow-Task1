# Main Flow Services and Technnology Internship Task 1
1. Dataset Selection
● Dataset: Download the Student Performance Dataset from a provided source.
○ File: student-mat.csv.
○ Contains columns like:
■ G1, G2, G3 (grades for three terms).
■ study time (hours spent studying weekly).
■ sex (gender: Male/Female).
2. Tasks to Perform
a. Data Loading
● Load the dataset using pandas.
● Display the first few rows using .head().
b. Data Exploration
● Check for missing values using .isnull().sum().
● Display column data types using .dtypes.
● Understand the dataset's size using .shape.
c. Data Cleaning
● Handle missing values (e.g., replace them with the median or remove rows).
● Remove duplicate entries using .drop_duplicates().
d. Data Analysis Questions
1. What is the average score in math (G3)?
2. How many students scored above 15 in their final grade (G3)?
3. Is there a correlation between study time (study time) and the final grade (G3)?
4. Which gender has a higher average final grade (G3)?
e. Data Visualization
1. Plot a histogram of final grades (G3).
2. Create a scatter plot between study time (study time) and final grade (G3).
3. Create a bar chart comparing the average scores of male and female students.
