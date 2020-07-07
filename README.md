# Credit_Card_Points

This is a sample application for developing a web application/Mobile App that can be used to store/display and handle a Credit Card Merchant Points system.  

The goal is to have:

1. A set of users to use the system.  We will store the billing address information for the users.
2. A set of credit cards that the users have within the context of the system.
3. A set of merchants that the credit card will use to accrue user points.  The merchants will need to have some configuration capability to determine how points are accrued.
4. We will also need to store transaction data for the merchants for the purpose of customer validation.


Deliverables of the system:

1. The initial goal of the system is to develop a general design of the system:  
a. We will need an ER diagram to show how the system will store the applications data. (Initial version is currently available)
b. We need a wireframe diagram to show how the web app will flow. (In Progress)

2. The next step will be to develop some live HTML based mockups using the design from deliverable 1b. 
a. The primary focus here will be to design how the CSS and HTML page designs will work.

3. Using the committed MVC framework develop the V and Model components.   This will probably involve using some data mocking since the DB will not yet be developed.

4. Using the committed MVC framework develop the back and integrate with the front end. 

5. Develop a testing mechanism into the system.

6. Get the system set up in a live setting such as Heroku to use for demoing purposes


Development Stack:

1. The project will require Java 8 platform for the backend and a postgres database. (Oracle Lite could be used as well).  
2. Other elements to stack include an MVC based framework.  Need to decide between Spring Framework VS Struts2.  The solution will lie in probably implementing
2 different projects.  One using Spring Framework and the other using Struts 2.  My initial approach will be Struts 2.
3. The front end approach:
a. will initially be using a Bootstrap based front end using JSP, Bootstrap CSS, and Javascript. 
b. an additional approach will use some modern framworks like React and AngularJS.



Notes:

1. Go back to the ER diagram and add name to the user table.
2. Another idea was to add a name to the Credit Card Table to provide a user friendly element to view the credit card by instead of just seeing a credit card number
