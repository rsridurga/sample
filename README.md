# sample
import java.util.*;
 
class Palindrome
{
   public static void main(String args[])
   {
      String original, rever = "";
      Scanner in = new Scanner(System.in);
 
      System.out.println("Enter a string to check if it is a palindrome");
      original = in.nextLine();
 
      int length = original.length();
 
      for ( int i = length - 1; i >= 0; i-- )
         rever = rever + original.charAt(i);
 
      if (original.equals(rever))
         System.out.println("Entered string is a palindrome.");
      else
         System.out.println("Entered string is not a palindrome.");
 System.out.println("over");
   }
}
