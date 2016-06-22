Getting and Cleaning Data: Course project week 4
Introduction
This repository follows the requirements of the Coursera course "Getting and Cleaning data", the fourth component of the Data Science specialization. The readme file will present the descriptive of the raw data, what I did with it and some lines on the codebook. 
About the raw data
The original dataset is Human Activity Recognition Using Smartphones Data Set. The features can be found in the x_test.txt and the activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file, and the trainings in subject_train.txt.
About the script and the tidy dataset
I created a script called run_analysis.R which will merge the test and training sets together. 
I downloaded the data and merged it. After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept. Appropriately labels the data set with descriptive variable names.
Finally, I saved the clean data in a second, independent tidy data set, called TidydataW4A, with the average of each variable for each activity and each subject
