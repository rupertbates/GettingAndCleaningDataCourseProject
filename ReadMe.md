Getting and Cleaning Data Course Project
========================================================

This repository contains my submission for the Coursera course 'Getting and Cleaning Data'  
It contains data sets relating to 'Human Activity Recognition Using Smartphones' sourced from 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones  
The raw files of this dataset are contained in the repo at ./UCI HAR Dataset

To run the code:

* Start R
* Set your working directory to the route of this project
* Run the file run_analysis.R

Output will be a tidy dataset in the file ./tidy-dataset.txt  

run_analysis.R will do the following:

* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement. 
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive variable names. 
* Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

A code book describing the format of this data is at ./CodeBook.md

