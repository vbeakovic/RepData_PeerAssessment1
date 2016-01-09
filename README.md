# Reproducible research - Course Project 1

## Introduction

This repository is a course project for the Reproducible Research Course on
Coursera. This is the first course project of the two projects that are part of this course.

## Data used for this assignment
This assignment uses data provided at the course website (<a href="https://www.coursera.org/">Coursera</a>). More  information about the data 
may be found in the the <a href="CodeBook.md">CodeBook.md</a> in the root of this repository.

## Scope of the assignment
The scope of the assignment is to produce a reproducible research analysing the number of stpes taken by an individual during a two months period.

## Files and directories in the repository
* figure directory - contains the plots produdes during the research
* data directory - contains a zip archive with the source data for the assignment
* CodeBook.md - info about the data, files, transformations and variables
* PA1_template.Rmd - R markdown file that allows to reproduce the research
* PA1_template.md - markdown file produced by renderging the Rmd file
* PA1_template.html - html file produced by rendering the Rmd file

## Explanation about the Rmd scripts

The script follows the guidelines of the course assignment and answers the following questions:

* Loading and preprocessing the data
    + Show any code that is needed to load the data (i.e. read.csv())
    + Process/transform the data (if necessary) into a format suitable for your analysis
* What is mean total number of steps taken per day?
    + Calculate the total number of steps taken per day
    + If you do not understand the difference between a histogram and a barplot, research the difference between them. Make a histogram of the total number of steps taken each day
    + Calculate and report the mean and median of the total number of steps taken per day
* What is the average daily activity pattern?
    + Make a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all days (y-axis)
    + Which 5-minute interval, on average across all the days in the dataset, contains the maximum number of steps?
* Imputing missing values
    + Calculate and report the total number of missing values in the dataset (i.e. the total number of rows with NAs)
    + Devise a strategy for filling in all of the missing values in the dataset. The strategy does not need to be sophisticated. For example, you could use the mean/median for that day, or the mean for that 5-minute interval, etc.
    + Create a new dataset that is equal to the original dataset but with the missing data filled in.
    + Make a histogram of the total number of steps taken each day and Calculate and report the mean and median total number of steps taken per day. Do these values differ from the estimates from the first part of the assignment? What is the impact of imputing missing data on the estimates of the total daily number of steps?
* Are there differences in activity patterns between weekdays and weekends?
    + Create a new factor variable in the dataset with two levels – “weekday” and “weekend” indicating whether a given date is a weekday or weekend day.
    + Make a panel plot containing a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all weekday days or weekend days (y-axis). 

## Acknowledgements
This assignment uses data from
the <a href="https://www.coursera.org/">Coursera website</a>.