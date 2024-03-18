# Scaler---Clustering
With the analytics vertical of Scaler, focused on profiling the best companies and job positions to work for from the Scaler database. We are provided with the information for a segment of learners and tasked to cluster them on the basis of their job profile, company, and other features. Ideally, these clusters should have similar characteristics.


Imported the dataset and do usual exploratory data analysis steps like checking the structure & characteristics of the dataset

Checked unique emails and frequency of occurrence of the same email hash in the data. Recording observation and inference, wherever necessary.

Checked for missing values and Prepared data for KNN/ Mean Imputation.

Removed special characters from the dataset by using Regex

Making some new features like adding ‘Years of Experience’ column by subtracting orgyear from current year

Manual Clustering on the basis of learner’s company, job position and years of experience
Getting the 5 point summary of CTC (mean, median, max, min, count etc) on the basis of Company, Job Position, Years of Experience
Merged the same with original dataset carefully and creating some flags showing learners with CTC greater than the Average of their Company’s department having same Years of Experience - Call that flag designation with values [1,2,3]
Doing above analysis at Company & Job Position level. Name that flag Class with values [1,2,3]
Repeated the same analysis at the Company level. Name that flag Tier with values [1,2,3]

Data processing for Unsupervised clustering - Label encoding and  One- hot encoding, Standardization of data

Unsupervised Learning - Clustering
Checked clustering tendency
Elbow method
K-means clustering
Hierarchical clustering 
