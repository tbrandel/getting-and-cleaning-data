# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does:

1. Downloads the dataset if it does not already exist
2. Load the activity and features
3. Loads both the training and test datasets, keeping only those columns with data
4. Loads the activity and subject data and merges those columns with the dataset
5. Merges the two datasets
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is `tidy.txt`.
