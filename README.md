# Average-Calc

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        int number;
        int counter = 0, total = 0;
        Scanner scanner = new Scanner(System.in);

        number = scanner.nextInt();

        for(int i = 1; i <= number; i++){
            if(i % 3 == 0 && i % 4 == 0){
                total += i;
                counter++;
            }
        }

        System.out.println("Average: " + total / counter);

    }
}
