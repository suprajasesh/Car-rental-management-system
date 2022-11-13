# Car-rental-management-system

1.Problem Statement :

Develop a database project for a car rental system. Agents can register and provide all details about the cars they wish to provide for rent with tariff and terms and conditions. Customers can register and choose the car they want to rent.  Agencies can update, add, delete cars in the database. Customers can view the variety of cars available for in rent in their budget.

Functional Requirement:
We require the following entities for the project:
1.	Admin: To store the details of admin
2.	Car_desc : To store the description of cars for rent
3.	Customer : To store the details of customer
4.	Rental : To store the rental details
5.	Payment : To store the payment details

Non-Functional Requirement:
1.	Security: Only authorized customers and admins are able to use the facilities
2.	Appropriate error messages are displayed 
3.	Data Inconsistency: All the appropriate scenarios have been handled

The Admin can encode 1 or more Customer information. The Customer can one or more cars from Car_desc. The Rental has only 1 detail of the Car_desc at a time or per transaction. The Admin processes one or more transactions through Payment along with Rental details and Customer Information.
 

Real Time application: 

This is widely used by online Car Rental Companies along with other details. 

Requirements:
We would require the following entities with appropriate relationships:
1.	Admin: To store the details of admin
2.	Car_desc : To store the description of cars for rent
3.	Car Images : To store the images of cars
4.	Customer : To store the details of customer
5.	Rental : To store the rental details
6.	Payment : To store the payment details
7.	Owner : To store the details of the car owner


Challenges:
1.	To effectively deal with cancellations and updates of information regarding customer details, car details and owner details.
2.	To maintain consistency of booking and cancellation data.
3.	To ensure that the payment transactions are carried out successfully
4.	To avoid duplication of data and anomalies.
5.	To avoid risk of overbooking
6.	To validate the authorization properly
