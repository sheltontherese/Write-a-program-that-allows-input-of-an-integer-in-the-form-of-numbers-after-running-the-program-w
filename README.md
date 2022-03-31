# Write-a-program-that-allows-input-of-an-integer-in-the-form-of-numbers-after-running-the-program-w
Write a program that allows input of an integer in the form of numbers, after running, the program will write that number out as letters.
import java.util.Scanner;

public class BaiTapJavaCoBan2 {
    public static void main(String[] args)
    {
       int n;
       System.out.println("Input an integer:");
       Scanner sc = new Scanner(System.in);

       n = sc.nextInt();

       switch (n)
       {
          case 0: System.out.println("No"); break;
          case 1: System.out.println("One"); break;
          case 2: System.out.println("Two"); break;
          case 3: System.out.println("Three"); break;
          case 4: System.out.println("Four"); break;
          case 5: System.out.println("Year"); break;
          case 6: System.out.println("Six"); break;
          case 7: System.out.println("Seven"); break;
          case 8: System.out.println("Eight"); break;
          case 9: System.out.println("Nine"); break;
          default:
             System.out.println("Only 0 - 9 :D");
             break;
       }
    }
}
