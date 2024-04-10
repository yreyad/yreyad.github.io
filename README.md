# CS1030
# yreyad.github.io
```
import java.util.Scanner;
 
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Ask user for quantity
        System.out.print("Please, enter the quantity: ");
        int quantity = scanner.nextInt();
 
        // Ask user for price
        System.out.print("Please,enter the price per item: ");
        double price = scanner.nextDouble();
 
        // Calculate the total cost
        double totalCost = quantity * price;
 
        // Display the total cost
        System.out.println("Total cost: " + totalCost);
 
        // Close the scanner
        scanner.close();
    }
}
 
```
