# hello-world
projetos-treinamento

package javaapplication2;

import java.util.Scanner;
        
public class JavaApplication2 {


    public static void main(String[] args) {
        int num2;
        int num1;
        Scanner ler = new Scanner (System.in);
        
        System.out.println("Digite um numero:");
        num1= ler.nextInt();
  System.out.println("Digite um numero:");
        num2= ler.nextInt();
        if (num1 > num2) 
            System.out.println(" maior numero " + num1+ " menor numero " +num2);
        
        else
            System.out.println(" maior numero " + num2+ " menor numero " +num1);
            
    }
    
}
