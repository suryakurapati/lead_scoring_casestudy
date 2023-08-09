# lead_scoring_casestudy
Identify potential leads who can convert in purchasing courses at 'X Education' institution

Core Objective:
An education company named ‘X Education’ sells online courses to industry professionals through their website.
People land on the website and either browse the courses or fill up a form for the course or watch some videos.
When these people fill up a form providing their email address or phone number, they are classified to be a lead.
Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.
Require to build a model that assigns a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance

Dataset:
Dataset of leads from the past with around 9000 data points with the target variable column as ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t converted.

Goal:
Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. 
A higher score would mean the lead is most likely to convert whereas a lower score would mean that the lead mostly not get converted.
