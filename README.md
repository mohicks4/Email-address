# Email-address, information of an email address
import java.util.Scanner;

public class EmailAddress
{
    
     public static void main(String[] args) {
         Scanner input = new Scanner(System.in);  
         
         String fName;
         String mName;
         String lName;
         String bDay;
    
         System.out.println("Enter your first name: ");
         fName = input.next();
         
         System.out.println("Enter your middle name: ");
         mName = input.next();
         
         System.out.println("Enter your last name: ");
         lName = input.next();
         
         System.out.println("Enter your birthdate (mm-dd-yyyy): ");
         bDay = input.next();
         
         System.out.println();
         
         System.out.println("Email: " + lName.toLowerCase() + fName.charAt(0) + mName.charAt(0) + "@sharkmail.com \n");
         
         System.out.println("Temp Password: " + bDay.substring(0,2) + bDay.substring(3,5) + bDay.substring(6,10) + "\n");
         
         System.out.println("*** This temporary password is very insecure. Please change it immediately! ***");
        }
    
}
