# cinema-room-manager
Simple CML-application to manage a cinema.

Hyperskill project "Cinema room manager" (Introduction to Java). Stage 5/5.

The user is asked to create a cinema with x-amounts of rows and seats in each row.
If the total number of seats in the cinema are < 60 then the ticket price is 10$.
If the total number is > 60 the ticket price is 10$ for the front half, and 8$ for 
the other half. 

The program presents the user with a menu:

1. "Show the seats" -> prints a view of all the seats in the cinema. 'S' indicates
the seat is empty, 'B' indicates the seat is taken. 

2. "Buy a ticket" -> lets the user choose the row- and seat number. If the seat is 
already taken the user is asked to enter a new row- and seat number.

3. "Statistics" -> prints information of the number tickets sold, number of tickets
sold in percentage, current income, and the max potential income if all tickets are 
sold. 

4. "Exit" -> stops the application. 
