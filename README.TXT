Project: better-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate conditional statements.
How to start this project: Create one or more TicketMachine objects.

47)no the balance does not change after the error message.
48)now that the condition is that amount is greater or equal to 0 the program takes 0 as a valid amount
50)the effect in figures project with circle was visible and invisible which uses true or false condition which is perfect for it.
51)in the naive ticketmachine the money inserted will be lost and doesnt matter the amount of money you enter the machine will print the ticket.
    in the better ticket machine we have a condition which checks the price with the money inserted and when printed
    will add the money to the total and remove that amount from balance which makes sure that the extra money will stay in the balance and if you did not 
    enter enough money in the machine it will show an error message.
52) yes the code will compile but now since we dont have the else part it will not show the error part saying that u need to inset more money.
53)the balance cannot be in negative because the code has the "if" statement to see if there is enough money before it subtracts price.
54)other arithmetic opererators in java are multiplication(*),divison(/) and modulo or remainder(%).
55)saving = price * discount;
56)mean = total/count;
59)this code does not give the same value as before the value it give is the value which is equal to balance after the money has been returned which is 0
    I ran the following tests to demonstrate that it does not
    1)new machine
    2)set price to 100
    3)insert 500)
    4)press refund balance and it gave me 0
60)the return statement in a method make the method to stop running and since the balance=0 was after the return it sees it as useless and thats what 
    makes it unreachable;
61)yes the code compiles. the diffrence that i can notice is that even if I set the price to 100 in the begining when I check the price in 
    the price field it will show 0. when you add int infront of price inside the contructor it sees it as another variable with the same name
    within the constructor the cost is assigned to this varible which is local not to the price field. the price field of the object was never initalized
    therefor it stayed 0.
62)
    
