# SDLC Activity Based Learning


## Train Ticket Booking System
This system focus on booking ticket of valid user whose credentials gets accepted.

User can login to system to check the Train details and booked tickets.

User can also verify that his/her ticket is booked or not.

## BADGES
1.CODACY BADGE
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/2e7065024d16448b806dddc8ae9c5892)](https://www.codacy.com/gh/patilsliet/PRACTICE_PRJ/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=patilsliet/PRACTICE_PRJ&amp;utm_campaign=Badge_Grade)

2.CODIGA

 CODE QUALITY BATCH
 ![Quality](https://api.codiga.io/project/32280/score/svg)

 CODE GRADE 
 ![Quality](https://api.codiga.io/project/32280/status/svg)

3.BUILD BATCH
[![C/C++ CI](https://github.com/patilsliet/PRACTICE_PRJ/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/patilsliet/PRACTICE_PRJ/actions/workflows/c-cpp.yml)

4.CPP CHECK'
[![CPPCheck](https://github.com/patilsliet/PRACTICE_PRJ/actions/workflows/cpcheck.yml/badge.svg)](https://github.com/patilsliet/PRACTICE_PRJ/actions/workflows/cpcheck.yml)



## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures
`5_Report`         | Updated ReadMe of all compoonents
`6_Video`          | Working Video

 

## Challenges Faced and How Was It Overcome

1. Multifile Programming was a new concept for me. Used YT to learn and execute it in project.
2. Overall project helped me to gain insights on industry standards.


## Learning Resources
1.https://www.cs.hmc.edu/~geoff/classes/hmc.cs070.200401/notes/multi-file.html#:~:text=A%20large%20C%20or%20C%2B%2B,be%20shared%20with%20other%20programs

2.https://github.com/stepin654321/MiniProject_Template/wiki

3.https://www.sololearn.com/learning/1089

4.You Tube





# Requirements
## Train Management System
## Introduction
The Project deals with the automation of the reservation and enquiry of the railway reservation system. It maintains all information starting from reservation to cancellation of tickets. It also acts as an enquiry system about the different trains available. This project aimed at the job simplification and reducing the manual work and hereby saving the time of physical visiting the railway stations.The main objective of the project is to manage the details of train, ticket booking, view the 
details of the passengers, available seats for the passengers, available trains for the particular route. It will track all the details about the booking, passengers and the train schedules.

## System Analysis (Research):
This system is basically concerned with the reservation and cancellation of the railway tickets to the passengers. The need of the system arise because as is the known fact that the India has the largest railway network in the whole of the world and to handle it manually is quite tough job. By computerizing it we will be able to overcome many of its limitations and will be able to handle it more efficiently. The handling of such records and data for such system is a very complex task if it is done manually but it can be made much easier if the system is computerized.

## System Features:
• System will allow the user to login in their respective account.

• Admin can edit the details of the trains.

• User will be able to book the tickets according to their needs.

• Tracks the information about train, bookings, passengers.

• Display the details of the booking.

• Print the booked tickets.

• User can cancel the booking.

## Benefits:
It will save the operating cost, reduction in paperwork and manual handling of the data, errors that can arises by doing the booking manually will also reduce and the better utilization of the human resources

## SWOT Analysis:

![image](https://user-images.githubusercontent.com/101458188/161370279-70dd7e4f-33a6-4455-85f3-8caef7e84da5.png)

## 5 W’s:
### Why: 
To reduce the manual work, along with that to save the time and efforts of Users to personally visit the stations for booking.

### Who:
Small and medium size organization can use it.

### What:
A simple and easy to use system for the Users to do all the activities related to online train ticket booking system such as reservation, cancellation and all other functions.

### When:
As the India has the largest railway network in the whole of the world and to handle it manually is quite tough job thus it is required now to design such systems which will help to do this job efficiently.

### Where:
This problem is expected all over the India

# Detail requirements
## High Level Requirements:

| ID | Description | Status |
|----|-------------|--------|
| HR_01|User Shall be able to login the system.|Implemented|
| HR_02|User Shall be able to book the ticket |Implemented |
| HR_03|User Shall be able to view the available trains. | Implemented |
| HR_04|User Shall be able to print the ticket|Implemented|
|HR_05|User Shall be able to cancel the ticket|Implemented|
## Low Level Requirement 
|ID|Description|Status|
|--|-----------|------|
|LR_01|	The user will be able to login successfully with the valid credential.	|Implemented |
|LR_02|	If user entered the incorrect login credentials then ‘SORRY !!!! LOGIN IS UNSUCESSFUL’ message should be displayed.|	Implemented|
|LR_03|If the wrong choice number is entered then message of ‘Invalid Choice’ should be displayed.|Implemented|
|LR_04|If all the required details for the booking the ticket are not provided then reservation should be unsuccessful	|Implemented|
|LR_05|	If the proper ticket holder name is provided then the ticket should be cancelled successfully.	|Implemented|



![image](https://user-images.githubusercontent.com/101458188/161373140-c8ba41d8-4024-426a-95c4-e968cc618f4b.png)
![image](https://user-images.githubusercontent.com/101458188/161373169-82ef6db7-0d0d-4005-9d31-0459615042e4.png)
![image](https://user-images.githubusercontent.com/101458188/161373250-dd8e0694-5c0b-40e4-b4e8-4a3a282ec948.png)
![image](https://user-images.githubusercontent.com/101458188/161373263-39da8fba-aa48-4768-a9cc-951f3ed7bd5b.png)
![image](https://user-images.githubusercontent.com/101458188/161373274-88337081-e8a9-4206-a3b9-88913e955479.png)
![image](https://user-images.githubusercontent.com/101458188/161373317-8b64de9f-b85e-4edc-a779-d3b7c2835a91.png)
![image](https://user-images.githubusercontent.com/101458188/161373327-1898e6b4-6a44-4922-b8fa-b23f77cdf2e0.png)
![image](https://user-images.githubusercontent.com/101458188/161373336-b8bc3c78-bd98-4fd5-88eb-fe361903808d.png)
![image](https://user-images.githubusercontent.com/101458188/161373347-3044f1a9-d152-4c3b-b73d-19b980f571fc.png)
![image](https://user-images.githubusercontent.com/101458188/161373372-f870fbb3-3a8e-4a52-a6e1-569b2a0c6096.png)
![image](https://user-images.githubusercontent.com/101458188/161373381-f2732a76-3faf-417a-9474-747a78bfef91.png)
![image](https://user-images.githubusercontent.com/101458188/161373389-7945963a-ef65-431e-be78-475a164ff8ac.png)


