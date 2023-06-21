# problem2.java
import java.util.Scanner;
public class Series {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter a number: ");
        int a = scanner.nextInt();

        int firstTerm = 1;
        System.out.print(firstTerm + " ");

        for (int i = 2; i <= a; i++) {
            int nextTerm = firstTerm +=2;
            System.out.print(nextTerm + " ");
            firstTerm = nextTerm;
        }
    }
}
