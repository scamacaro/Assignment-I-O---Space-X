# Assignment-I-O---Space-X
Assignment I/O - Space X
/*
 Sanyerlis Camacaro - Sanyerliscamacaro@uat.edu - CSC203
 Assignment I/O - Space X

 To write first Java program that displays output and input from user.
 */

//This library allows us to use the Scanner class and get user input.
import java.util.Scanner;

// Create the Main class and main function for my java program
public class Main{
    //Create the main function for my java program
    public static void main(String[] args) {
        //Display a title of Starbase 13 for the user.
        System.out.println("\n\n\t *** Mission: Starbase 13 ***\n\n");
       
       // Now above the description, add code that adds a computer greeting like "I am MACHINA X22, what is your name?" 
       //to the top of the user's display.
       // write code to get the user name and place it into a string variable.
       //adds a computer greeting like "I am MACHINA X22, a Programmed Algorithmic Computer, What is your name?"
       System.out.println("\nI am MACHINA X22, a Programmed Algorithmic Computer, What is your name? ");
       //Write code to get user name and place it into a string variable.
       Scanner input = new Scanner(System.in);
       String  userName = input.nextLine();
       //Display message that identity is confirmed."
       System.out.println("\nIdentity confirmed. Thank You.");
       //Display the user name with a welcome message like "Hello User, Welcome to Starbase 13."
       System.out.println("\nHello, " + userName + ", Welcome to Starbase 13. We've been expecting you.");
       //Displays message of current year 2491. 
       System.out.println("\nCurrent Year is: 2491.");

        //Write code that displays a description of space SpaceX's new space station
        //"Starbase 13".
        // Story telling starts.
        System.out.println("\nStarbase 13 is the new building for scientific research inside SpaceX Spaceship.\n "); // LINE 1
        System.out.println("The mission of Starbase is to find extraterrestrial life while orbirting, and watching over planet EARTH.\n"); // LINE 2
        System.out.println("We believe that Extraterrestrials can guide us with advanced technology to help us save EARTH from global warming.\n"); // LINE 3
        System.out.println("This may seem like a scary mission because of the risks if we encounter dangerous Extraterrestrials.\n"); // LINE 4
        System.out.println("Only the best agents have access to our mission, and " + userName + " you are one of our BEST agents.\n"); // LINE 5
        System.out.println("We hope that you're READY for this mission because it STARTS in 3,2,1...\n"); // LINE 6
        System.out.println("Click DELETE to exit mission.\n"); // LINE 7
    }
    // End main.
        
    }
    // End Starbase13 class.
