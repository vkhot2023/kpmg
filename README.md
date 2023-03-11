# KPMG CERTIFICATION PROJECT

Sprocket Central Pty Ltd specializes in high-quality bikes and accessible cycling accessories for riders. 

1 Their marketing team is looking to boost business by analyzing their existing customer dataset to determine customer trends and behavior.we need to recommend the TOP 1000 customers that shall target by Sprocket Central Pty Ltd to drive the most value for the organization.  

2 Client also has New list of 1000 potential customers do not have any prior transaction history with the organization.
 Their marketing team required analyzed data that could help optimize resource allocation for targeted marketing.
Using this dataset, we need to recommend high-value customers to optimize resource allocation for targeted marketing. 



## Dataset
raw dataset: https://github.com/vkhot2023/kpmg
## Development process
we are going to follow 5 steps to successfully complete this project:

* Project statement
* Data Exploration
* Dashboard Development
* Model Development
* Data Analysis

###  Project statement

In this process, we are going to defined Project Problem statement and what will consider as successfull completion of project.

Problem statement:
Client has specific 2 requirements:

1  Need Top 1000 most valuable customers from existing customer List

2  Top 20% Potential customers from new target customer List

  project will consider as successfull completion when both client requirements resolved.

  ### Data Exploration

  In this process, we perform 2 tasks: Data Quality Assessments and Data Distribution

Data Quality Assessments:
we extract raw data which contain excel workbook with 4 different sheets namely Transactions,CustomerDemographic, CustomerAddess and NewCustomerList.
  
 We found certain data quality issues with respect to datasets, we perform quality assessments such as Data Accuracy, Data Completeness, Data Consistency and Data Currency
Detail of this assessment could find out in PPT Document.

Link: https://github.com/vkhot2023/kpmg/blob/main/kpmg%20ppt.pdf

we use data cleaning techniques to convert data into suitable format

Data Distribution:
We explore data to get basic understanding of datasets. We explore data based on   
1  Age 
2  Gender    3  jobs
4  wealth
5  state

Finding of this distribution could find out in PPT Document.

Link: https://github.com/vkhot2023/kpmg/blob/main/kpmg%20ppt.pdf

### Dashboard Development

In this process, we developed Dynamic Dashboard using Microsoft PowerBI tool. this dashbaord capable to provide specific information as per User requirements. User can choose pre-requistic condition to obtain data

Screenshot:

                                                   Existing Customer Dashboard:

![1](https://user-images.githubusercontent.com/115641570/222718879-dfb0aefd-5441-4514-a011-90d50bf465a8.PNG)


                                                   New Customer DashBoard:

![2](https://user-images.githubusercontent.com/115641570/222719100-63ff08c2-46d6-47a5-ba7b-88cd583bfdd7.PNG)

### Model Development:

In this process, we developed RFM model to provide list of high potential target customers.RFM analysis is utilize to determine which customers need to target to increase business. Model applied to both existing and new customers
we divide customers in 6 categories namely:
1 Platinum 

2 Premium Gold

3 Standard Gold

4 Silver

5 Bronze

6 Lost Customers

Their values are in order of Platinum > Premium Gold > Standard Gold > Silver > Bronze > Lost Customers

Describtion of this Titles explained in PPT Document

Screenshot of DashBoard:

![3](https://user-images.githubusercontent.com/115641570/223104375-c8939597-5c95-4989-b258-116978f888b7.PNG) 

 
 Above Dashboard is interactive. User can applied thier own combination on DashBoard.
we applied different analysis on this data. Customer segmentation according to their Title completed with the help of RFM Model.     
More information could find out in PPT Document

Link: https://github.com/vkhot2023/kpmg/blob/main/kpmg%20ppt.pdf

### Data Analysis

After successfully completion of Model development step, we achieved customer segmentation based on thier potential customer capabilities

                                                       Existing Customers  
<img src="https://user-images.githubusercontent.com/115641570/223116370-0aa6014e-77ec-4e94-a836-daf6133fcf5b.png" width="450" height="300" /> <img src="https://user-images.githubusercontent.com/115641570/223120003-26d69581-a2c2-4fed-bc1d-01e0ab14c52b.png" width="450" height="300" />

                                                       New Customers
<img src="https://user-images.githubusercontent.com/115641570/223122241-41249a12-64d6-4f53-9865-ce4b63619ee2.png" width="450" height="300" /> <img src="https://user-images.githubusercontent.com/115641570/223122549-cbe2f6a0-f63d-4a7c-8837-94cd47fef252.png" width="450" height="300" />

* As we need Top 1000 customer list from existing Customer Dataset so we select Platinum and Premium_Gold category customers. we select whole Platinum category with 570 customers and 430/486 customers from Premium_Gold Category

* As we need Top 20% customer list from New Potential Customer Dataset so we select Platinum, Premium_Gold, Standard_Gold category customers. we select whole Platinum category with 37 customers, whole Premium_Gold Categoryand 134 customers and 29/186 customers from Standard_Gold Category

we analysed this customer, we obseved following trend:

![image](https://user-images.githubusercontent.com/115641570/223144775-1b02ad05-1531-44d5-8c63-7b27226f62b6.png)

## PowerBI Project:

Link: https://github.com/vkhot2023/kpmg/blob/main/UPLOAD%20kpmgpowerbi.pbix

## Project Completion 

project completed by VISHAL JAGANNATH KHOT
