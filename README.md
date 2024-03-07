# Student-Management-System (SQL project)    

Student-Management-System deals with student details,course details,batch details etc. Here, the dataset made, consists of details of students and various courses joined by them.   
1) Student details consists of sid,sname,sdob,scity,squal,semail,sphone
2) Course details consists of courseid,coursename,coursecategory,coursefees,courseduration,batch_end_date
3) Enrollment details consists of batchid,sid,edate,weekday,dayname
4) Batch details consists of batchid,bsdate,datetime,bstrength,courseid

### Objective
To meet a solution for storing and managing student's records accurately by education institutes during enrollment of specific courses they choose.  
Different reports anad queries can be generated based on the data related to students and courses

### Approach Used:
Exploratory Data Analysis (EDA):

Exploratory data analysis is done to answer the following questions :

1) Display all undergraduate student whose name starts with ‘S’ and is of length between 5 and 20.
2) Display the student who are senior citizen (>=60).
3) Display student who were born after 1st of June 1980.
4) The student are suppose to only provide mobile numbers .All mobile numbers should start with  zero followed by 10 digits.
5) All emails should have “@” anywhere after the first character and should end with “.com”.
6) Display the name and email of student who have a Gmail account.
7) Display the above record but do not consider invalid email id.
8) Display the qualification and the total number of students registered based on their  qualifications.
9) Display the full name of the month and the total number of students who are having their  birthday in that month.
   (Alias use “Month” and “Total”)
10) Display the student name that was born in a leap year ordering by student name and year of  birth.
11) Display student whose city is Kolkata as “HomeStudent ” and others as “DistanceStudent”  under a column “Remarks”.
12) Display count of students having no contact information. (Either email or phone).
13) Display coursename having above average fees.
14) Display coursename where fees are less than the average fees of its category.
15) Display student name having duplicate email ids.

### Using Joins
    
16) Display batchid, coursename, batch start date, batch end date for all batches. 
17) Display all batchid having a difference of 10 hours and less between its starting and ending date
18) Display student who enrolled for the batch after its start date.
19) Display the studentid, studentname , totalfees for all student.
20) Display the coursename having the highest enrollment.
21) Display student name having similar name but different email ids.
22) Display the course name fetching the 2nd highest revenue.
23) Which among the following have the highest enrollment? (Graduate,Undergraduate or  postgraduate).
24) Display student name,age[Alias],coursename,batchid,batch_start_ date,batch_ end _date 
