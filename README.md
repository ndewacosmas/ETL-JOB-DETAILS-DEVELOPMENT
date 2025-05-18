# ETL-JOB-DETAILS-DEVELOPMENT
ETL-JOB-DETAILS-DEVELOPMENT SECOND ATTEMPT


This area are used to extract data from source, The main source of data of this project is kaggle.com, and the data which are extracted are excuted and transform and loaded to the PostgreSQL Data base for processing and storage by the use of the Machine learning


The resulted table will be apeared like the follows

![ETL WORK](https://github.com/user-attachments/assets/6659a396-40c3-4f3c-b2ed-11d2bfa6b6b0)







The data which are extracted frm Kaggle.com are called students performance in examination, the Marks secured by the students in high school Students from the United States which are published in 2019. under this project and data which are extracted had the following categories of data which are

. Gender of the student who are set for the examination out of which 52% are female and 48% are male

.A race of the students which are 32% are group C, 26 are group D and 42 are depend on any other group

. Parental level of student out of which 23% of the student are some colleges, 22% of the students are associate's degree and 55% of the student are in other levels

. Lunch of the student out of the student it show that 65% of the student are Standard and 36% of the students are Free/reduced

.Test Preparation out of the students 64% of the student did not conduct the test preparation and 36% of the student complete the test preparation

The Extracted data was extracted from https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data and executed by the use of the machine learning

schedule of the work The job schedule was extracted which depend on the time of the extracting the data, because according the Architectural designing of the application system it show that the system will be updated every quarter by usingi the updation mechanism which found in the ETL. Test mode =Jobs runs every one mini production mode = Job runs every quarter

The execution mode can depend on the area of updation and execution_MODE variable under etl in the Docker compose.yaml file.

Test Mode: environment: -Execution_Mode= test

Production Mode: -Execution_Mode=Production
