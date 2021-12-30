# Web Scraping & EDA on naukri.com

##Aim:

• To know, how many current notifications are on the job, when will we use the *Data keyword.

1. Company, Job Name & City wise.
2. Company wants, how many job skills required for the job.
Reference: https://www.naukri.com/data-jobs

###Key Point

• Project Overview.
• Libraries Intro and uses.
• Web Scraping Technique and code.
• Data Cleansing and Engineering Featuring.
• Exploratory Data Analysis.
• Observations.
• Conclusion

###Introduction

In the project, I wanted to know, if the user will type *Data 
on the keyword on Naukri then how many jobs will display 
for the people.

• The project focus on the Naukri Web Notification, which 
notification display by the outside companies recruiters 
and using web scrapping I am collecting all data which 
are related to the Job content, Payable amount, 
Experience etc..

• With the help of Python pandas & Numpy concept, we 
will create the DataFrame and save in the form of Excel. 
Then we will apply some Data cleansing, Engineering 
Featuring concept and EDA analysis.

• Aim: my aim to write this code, because, I want to know 
which city hiring the maximum count of people for 
which profile with key skill.

###Final, Exploratory Data Analysis Observations Summary:

• Candidates type the ***Data Keyword.

Positive:

❑ Find total 300 Raw Job Notification, but Maximum count of the job 
Notification related to the *Data Engineer & *Data Entryfor South 
Region ( Hyderabad, Bangalore, Chennai etc.. ) 

❑ Candidate should have a Max 3 year Experience and these all company 
hire the Fresher also.

❑ All company mentioned in the job Notification 0-X payable amount 
(Annum). I think, directly, Company want to tell your job interview will 
decide how much we will provide the salary per annum.
Negative:

❑ For the Data Entry : Company provide the 0- 7 Lakh package but 
person should have a 3 Year experience. But for the Data Scientist 2 
Year experience and they will provide 3.5-4.5 Lakh only. 
*** We have to think about it ... is it real or fake

• My approach, if someone wants to find a job, please type in full key points like data engineer, data 
scientist, data analyst because if the users only types **data, the user may get an unnecessary job 
name, that I mentioned. Has done in the last slides.

• Individuals have to focus on core skills according to the job or profile name.

• Data Scientist
Naukri not the best platform for the Job. Because company hiring a person with 3 years and 
the payable amount is 3.4-4.5K only
