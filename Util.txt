import java.util.Scanner;
import java.util.Scanner;

public class Util{

public void CalcularIMC(){
Scanner scanner = new Scanner(System.in);
double peso;
double altura;
double imc;

      System.out.println("Peso: ");
      peso = scanner.nextDouble();
      System.out.println("Altura: ");
      altura = ler.nextDouble();
      scanner.nextLine();

imc = peso / (altura * altura);

System.out.println("Seu IMC: "+imc);

}

public void ConverterTemperaturas(){
Scanner scanner = new Scanner(System.in);
double tc;
double tf;

      System.out.println("Temperatura em Fahrenheit: ");
      tf = scanner.nextDouble();

tc = (tf - 32) * 1,8;

      
System.out.println("Temperatura em Celsius: "+tc);

}
}
