import java.text.DecimalFormat;
import java.util.Scanner;

public class Main {
    private static final DecimalFormat DF = new DecimalFormat("0.00");


    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Please enter your weight(Kg): ");
        double weight = scanner.nextDouble();

        System.out.print("Please enter your height(Cm): ");
        double height = scanner.nextDouble() / 100;

        double bmi = Double.parseDouble(DF.format(weight / (height * height)));
        System.out.println("Your BMI IS " + bmi);

        if (bmi <18.5){
            System.out.println("You're too light");

        }else if(bmi <24) {
            System.out.println("You're is normal");

        }else if (bmi < 30) {
        System.out.println("You're little overweight");

}        else {
        System.out.println("You're overweight");
    }
    }
    }
