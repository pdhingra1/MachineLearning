Workforce Analytics To Predict Job Change of Data Scientists: A Data Driven Machine Learning Approach

Purpose: The present study aims to -

Identify and understand the factors that indicate if a person will work for the company or will not.
Build different classification models using candidate data to predict the probability of candidates looking for candidates that will continue to work for the company or will look for a new job.
** Aim –** To predict the attrition rate of managers and to study the key factors behind data scientist’s leaving their job

Data Collection – Data is obtained through secondary research. Dataset is designed such that Human Resource (HR) researchers can add value to their organisation by predicting the attrition rate.

Understanding the data – It contains information of approximately 20,000 managers from different companies, in the mid pandemic period. Information is related to demographics, education, previous work experience etc.

About the dataset – Data is highly imbalanced. So, we are using a technique called SMOTE in Python to overcome this challenge. Most features are categorical (Binary, Nominal, Ordinal) with high cardinality. We have converted them to numerical before running the Machine Learning models. Data contained several missing values which were also computed.

Exploratory Data Analysis – The matplotlib library of python was used to visualise each and every feature that could be a reason for a manager leaving his organisation. Heatmaps, bar graphs and pie charts were chosen for the same.

Model Building- Dataset was divided to training and testing sets and we applied certain machine learning models on the training data. Models chosen were bagging techniques like Logistic Regression, Random Forest Classifier, Naïve-Bayes, K-Neighbours Classifier, and boosting methods like XGB Classifier and Gradient Descent Boosting.

Results – Accuracy of each model was studied the best model was taking forward to find out the feature importance.

Observations:

Gender:

Majority of the candidates are Males.
Male candidates are not really looking for a job change.
Female candidates look little more inclined to job change.
Relevant Experience:

Most of the candidates have relevant experience.
We can observe that there quite a few candidates with relevant experience who are not looking for a job change.
Candidates with no relevant experience are keener to change job.
Enrolled University:

Most of the persons are having no enrolment in any university and those without any enrolment have no interest in changing their job.
Part Time course enrolled students are very less and they also don’t want to change.
Full time enrolled is not very much also but in proportion they have higher chance of changing the job than others.
Education Level:

Majority of the candidates are graduates.
Irrespective of the education levels, we can observe that there is a very less chance of candidates who would look for changing job. Of those interested we can see that Graduates are the one more inclined towards looking for job change.
Major Discipline:

Most of the candidates have the major discipline as STEM and these candidates generally do not show much tendency to change the job.
Of the people showing tendency to change jobs, they come from STEM/Business backgrounds.
Experience:

People who have experience less than 1 year have more tendency to change their job while those with more than 20 years of experience have very less tendency of changing jobs
As experience increase, tendency to change the job becomes lesser.
Company Size:

Most of the candidates work in companies with employee strength between 50 to 500.
Candidates currently employees with companies (50-99) are more keen for job change.
Company Type: Most of the candidates are working in Pvt Limited Companies and those are the ones keener to job change. Last New Job: Candidates who have changed their jobs in the past one year are more probable to look for job change.
