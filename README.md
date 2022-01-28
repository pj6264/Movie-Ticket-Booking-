# Movie-Ticket-Booking-

A mini project by:

Ja Prarthanaa (RA2111009010092)

Aayush M V (RA2111009010093)

This project is to implement a simple Movie Ticket Booking System where a user can book and print a ticket under his/her name and contact number. 
Arrays, Structures, Pointers, Functions and Text files are used in this project

User details along with the tickets booked are stored in a text file. 
The text file is then used to display the contents of old transaction records. 
The working of the project is explained below

Working:
The program is a menu driven program wherein the user has three choices:
	1 - View All Movie
	2 - Book Ticket
	3 - View All Transactions

The user can choose option 1 to view the list of currently screening Movies along with the Movie Code and the Number of Seats available, which are stored in an array.

When a user chooses option 2, he/she is taken to Ticket Booking Menu. 
Here the user must first type the movie code to retrieve Movie Details and Ticket Price along with the Show Timings. 
Next user details such as Name and Mobile Number are inputed to book tickets. 
Number of Tickets and Show Timings are chosen. 
These details are automatically stored in a text file.

A bill is printed along with the movie ticket. The printed Bill displays Name, Mobile Number, Movie Name, Total Seats, Total Amount and Show Time

To view previous booking transactions, the user can choose option 3. Details of old movie tickets are retrieved from text file and displayed to the user.

Since there are three choices present in the menu, the program works if the choice input is either ‘1’, ‘2’ or ‘3’. 
Any other inputted value will simply result in the menu being displayed again. 
If ‘4’ is entered, the program quits.
