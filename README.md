# Railway-reservation-System

Abstract
The railway reservation system facilitates the passengers to enquire about the trains available on the basis of source and destination, booking and cancellation of tickets, enquire about the status of the booked ticket, etc. The aim of case study is to design and develop a database maintaining the records of different trains, train status, and passengers. The record of train includes its number ,name, source, destination, and days on which it is available, whereas record of train status includes dates for which tickets can be booked, total number of seats available, and number of seats already booked. The database has been developed and tested on the Oracle. Passengers can book their tickets for the train in which seats are available. For this, passenger has to provide the desired train number and the date for which ticket is to be booked. Before booking 
a ticket for a passenger, the validity of train number and booking date is checked. Once the train number and booking date are validated, it is checked whether the seat is available .If yes, the ticket is booked with confirm status and corresponding ticket ID is generated which is stored along with other details of the passenger. After all the available tickets are booked, certain numbers of tickets are booked with waiting status. If waiting lot is also finished, then tickets are not booked and a message of non-availability of seats is displayed. The ticket once booked can be cancelled at any time. For this, the passenger has to provide the ticket ID (the unique key). The ticket ID is searched, and the corresponding record is deleted. With this, the first ticket with waiting status also gets confirmed.

Introduction
Database is an organized collection of data. The data is typically organized to model aspects of reality in a way that supports processes requiring information. A DBMS makes it possible for end users to create, read, update and delete data in a database. The DBMS essentially serves as an interface between the database and end users or application programs, ensuring that data is consistently organized and remains easily accessible. The DBMS manages three important things: the data, the database engine that allows data to be accessed, locked and modified and the database schema, which defines the database’s logical structure. These three foundational elements help provide concurrency, security, data integrity and uniform administration procedures. The DBMS can offer both logical and physical data independence. That means it can protect users and applications from needing to know where data is stored or having to be concerned about changes to the physical structure of data. The main purpose of maintaining database for Railway Reservation System is to reduce the manual errors involved in the booking and cancelling of tickets and make it convenient for the customers and providers to maintain the data about their customers and also about the seats available at them. Due to automation many loopholes that exist in the manual maintenance of the records can be removed. The speed of obtaining and processing the data will be fast. For future expansion the proposed system can be web enabled so that clients can 
make various enquiries about trains between stations. Due to this, sometimes a lot of problems occur and they are facing many disputes with customers. To solve the above problem, we design a data base which includes customer details, availability of seats in trains, no of trains and their details.

Design:

<img width="410" alt="image" src="https://github.com/rucha1999/Railway-reservation-System/assets/76157534/a931aa0b-e665-48a2-8ec4-4c093ad3a7e0">


<img width="407" alt="image" src="https://github.com/rucha1999/Railway-reservation-System/assets/76157534/8b8353fd-f9f2-4458-bcc0-8ef41b3b6657">

Output:

<img width="253" alt="image" src="https://github.com/rucha1999/Railway-reservation-System/assets/76157534/c08b18b7-26d9-47bf-b496-91ffc48e7b8f">


<img width="178" alt="image" src="https://github.com/rucha1999/Railway-reservation-System/assets/76157534/71ad4df6-e7d3-4a3c-8c08-f0c04d647ea1">


<img width="155" alt="image" src="https://github.com/rucha1999/Railway-reservation-System/assets/76157534/db1e277a-e79e-49a9-be79-d5ffa9430e58">

Applications:
• The railway provide this facility the the journey become easy because the we can book or reservetion of ticket online with help of internet it is reduce the physical and mental stress go to station standing line for booking ticket but irctc launch this facility journey is easy because once we and it is also cheap in rate and we can travel through whole india.
• They Work 24/7
• Hassle-Free Management of Bookings
• Payments are Easier and Faster
• Cut Your Workload

Conclusion:
In our project Railway reservation system we have stored all the information about the Trains scheduled and the users booking tickets and even status of trains, seats etc. This data base is helpful for the applications which facilitate passengers to book the train tickets and check the details of trains and their status from their place itself it avoids inconviniences of going to railway station for each and every query they get. We had considered the most important requriments only, many more features and details cand be added to our project inorder to obtain even more user friendly applications. These applications are already in progress and in future they can be upgraded and may become part of amazing technology.

References
1. C. J. Date, A. Kannan and S. Swamynathan, An Introduction to Database Systems, Pearson Education, Eighth Edition, 2009.
2. Abraham Silberschatz, Henry F. Korth and S. Sudarshan, Database System Concepts, McGraw-Hill Education (Asia), Fifth Edition, 2006.
3. Database System Concepts by Abraham Siberschatz
4. “An Introduction to Database System” by Amit Desai
5. SQL Research Paper by “Aruna Prasad Gupta

