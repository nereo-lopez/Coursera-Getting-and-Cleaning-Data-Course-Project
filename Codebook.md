---
title: Coursera: Getting and Cleaning Data - Project
author: Nereo López
date: 07/07/2020
---

# Project Description
This is a peer reviewed project for the Getting and Cleaning Data Course Project from Coursera

# Collection of the raw data
Raw data was provided by the course at: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

# Creating the tidy datafile


# Guide to create the tidy data file
The data file was created by organizing the data frames in variables, and merging both: the 
training data and the subject data together.

#Cleaning of the data
All data was organized in different variables and then was structured via R, using internal functions and the dyplr library.

#Description of the variables in the tiny_data.txt file

These are the Identifiers used by the script :

Subject: the ID of the Subject
Activity: the Name of the Activity performed by the subject when measurements were taken

There are the variables used in the script:

#Features
  This considers all features of the subject, like acceleration, body mass, energy, etc.
#Activities
  This considers all activities performed by the subject: walking, climbing, sitting, standing, etc.
#x_test
  Test subject in X axis
#y_test
  Test subject in Y axis
#subject_train
  Test subject for training 
#x_train
  Training subject x axis
#y_train
  Training subject y axis
