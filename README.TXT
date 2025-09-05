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

Q2: The value returned from the machines balance after it was printed would be $1000
Q3: Once I inserted multiple values it would tell me to insert at least more of the given value
If I were to insert too much money, for example $10,000; it would just print out 100 cents four times
If I don't insert enough money then it won't show in the print ticket 
Q5: The second ticket machine would work the same as the first one; the printed ticket would look the same as the other one 
Q6:Student classes can be written differently than LabClass. Like student can be written as student public class;LabClass can be written as public Labclass class.
Q7:In this case if we try to mix class and public in the TicketMachine editor it would be an error
Pressing the compile button explains what the errors are and what you need to fix
The type is usually found in the middle of the fields
Q12:For example: private int count; the type is "int"; private Student representative; the type is "Student"; private Server bost; the type  is "Server".
Q13:The name of the field: private boolean alive; name would be "alive"; private Person tutor; name: "tutor"; private Game game; name: "game"
Q14:The class names from the following two examples would be "private"
Q15:When it comes to the TicketMachine class private int price; no matter what order you put those three words the editor will detect an error and show you what you need to fix.
Q16:After every field declaration it is important to always put a semicolon at the end, as it will detect an error in the code.
Q17: private int status;
Q18: public
Q19: two parameters
The types would be string and price
Q20: The constructors parameters should be stored somewhere persistent so you would be able to see their values
I wouldn't be able to guess what the Book claass's fields might be; I wouldn't say that we 100% know the names of its fields 
Q21: 
public Pet(String petsName)
{ 
  this.name = petsName;
}
Q23: One difference between the header of getBalance and getPrice is that one method uses int and the other uses void;
When it comes to the body of getBalance method it uses = whereas getPrice method doesn't.
Q24: "What is amount in the ticket machine"
Q25: Yes, everything in the body needs to be compiled in order to work. We can see that in the accessor method it now changed from void getAmount.
Q27: Once I remove getPrice the error detects that it's not a statement.
Q28: For getPrice it has an integer whereas printTicket has void.
Q29: No, Both insertMoney and printTicket don't have return statements because it is a system output
Q32: Yes, the method changes the value of balance since the object state is mutated.
Q33:public void discount(int amount)
{
   price +price - amount;
}

Q34: public void setAge(int currentAge)
     {
          this.age = currentAge;
     }

Q35:  public void setalive(int boolean)
      {
          this.setalive = alive;
      }

Q36: Due to the change the value of the price field return to a value of zero.
Q37: System.out.println("My cat has green eyes.");
Q38: public void prompt(int newPrompt)
    {
        // please insert the correct amount of money 
       
        System.out.println("insert correct amount of money");
        
    }

Q39: The actual price of the ticket won't show meaning that th word "price will show since you won't be requesting the actual price.
Q40: The # price and cents word will show since they're in quotation marks.
Q41: public void showPrice(int price)
    {
        // the price of a ticket is xyz cents
        
        System.out.println("the price of a ticket is xyz cents");
    }

Q42: Yes, they both show the same output due to both having the same method call but different values
Q44: Once I created a ticket machine object in bluej it had an effect on the object. Meaning that it didn't have the same methods as the actual TciketMachine.
Q46: No it doesn't need any parameteres since it has a total state and it's a mutator because it changes the state instead of getting data/information in any way.
