# SamOrNot2
String exercise
package stringAssignments;

import java.util.Scanner;

public class SameOrNot2 {
  public static void main(String[] args) {
	   
	  Scanner input = new Scanner(System.in);
	  
	  System.out.println("Enter please first word");
	  String word1 = input.nextLine();
	  System.out.println("Enter please second word");
	  String word2 =input.nextLine();
	  
	  if(word1.charAt(0)==word2.charAt(word2.length()-2) || word1.charAt(1)==word2.charAt(word2.length()-1)) {
		  System.out.println("true");
	  } else {
		  System.out.println("false");
	  }
	  input.close();
	  
}
}
