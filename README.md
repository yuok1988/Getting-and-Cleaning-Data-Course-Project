This is the course project for the Getting and Cleaning Data Coursera course.
The included R script, Run analysis.R, conducts the following:
Download the dataset from web.
Read both the train and test datasets and merge them into x(measurements), y(activity) and subject.
Load the data(x's) feature, activity info and extract columns mean and standard. Also, modify column names to descriptive.
Extract data by selected columns, and merge x, y and subject data. Also, replace y column to it's name by refering activity label.
Generate Tidy Dataset that consists of the average (mean) of each variable for each subject and each activity. The result is shown in the file tidy_dataset.txt.