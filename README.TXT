Project: naive-ticket-machine
Authors: David Barnes and Michael Kolling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Fourth edition
   David J. Barnes and Michael Kolling
   Pearson Education, 2008

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.

See the doc directory for the chapter PDF

2.2) What value is returned if you check the machine’s balance after it has printed a ticket?

	The balance is now 0.

2.3) Do you notice anything strange about the machine’s behavior?

	No matter how much money I enter, the balance always resets to zero after printing a ticket.
 
What happens if you insert too much money into the machine – do you receive any refund?
	
	No refunds are offered.

What happens if you do not insert enough and then try to print a ticket?

	If I did not insert enough money, a string is returned that states "Ticket price: [] cents. Your total is []." Regardless of whether you have enough to pay for the ticket, the same string pops up.

2.6) Write out what you think the outer wrappers of the Student and LabClass classes might look like – do not worry about the inner part.

	public class Student{}
	public class LabClass{}

2.7) Does it matter whether we write
public class TicketMachine
or
class public TicketMachine
in the outer wrapper of a class?

	It does matter that public comes before class. The access modifier must come before the class.

2.8) Check whether or not it is possible to leave out the word public from the outer wrapper of the TicketMachine class.

	It is possible.

2.9) Make a list of the names of the fields, constructors, and methods in the TicketMachine class:

	Fields: price, balance, total, and ticketNumber
	Constructor: TicketMachine()
	Methods: getPrice(), getTicketNumber(), getBalance(), insertMoney(), calculateTotal(), incrementTicketNumber(), printTicket()

2.10) Do you notice any features of the constructor that make it significantly different from the other methods of the class?

	The constructor sets a default value to all of the fields.

2.11) What do you think is the type of each of the following fields?
private int count;
private Student representative;
private Server host;

	count is an integer, representative is a Student, host, is a Server.

2.12) What are the names of the following fields?
private boolean alive;
private Person tutor;
private Game game;

	The fields are alive, tutor, and game.

2.13) In the following field declaration from the TicketMachine class [private int price;] does it matter which order the three words appear in?

	It does matter. The access modifier goes first, then the field type, then the field name.

2.14) Is it always necessary to have a semicolon at the end of a field declaration?

	Always.

2.15) Write in full the declaration for a field of type int whose name is status.
	
	private int status;

2.16) To what class does the following constructor belong? [public Student(String name)]

	It belongs to class Student.

2.17) How many parameters does the following constructor have and what are their types?
public Book(String title, double price)

	2 parameters: a String and a double.

2.18) Can you guess what types some of the Book class’s fields might be? Can you assume anything about the names of its fields?

	Book will have a field for a book title and a book price. The fields will likely be some variation of title and price.
		 
