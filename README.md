# fila-do-banco-
Elabore um programa que simule uma fila de atendimento bancário. O programa deve ler o nome de 3 pessoas (clientes do banco), armazenando-os em uma fila.
 import java.util.Scanner; 
 
public class Main { 
 
    public static void main(String[] args) { 
 
    String[] nomesFila = new String[3];     // Declarando o array com 3 posições.
    Scanner nome = new Scanner(System.in); 

    String nome1 = nome.nextLine();   // recebendo a posição 0 (zero) do array
    String nome2 = nome.nextLine();   // recebendo a posição 1 (um) do array.
    String nome3 = nome.nextLine();   // recebendo a posição 2 (dois) do array.

    System.out.println(nome1 + " - esta na posicao: 1");
    System.out.println(nome2 + " - esta na posicao: 2");
    System.out.println(nome3 + " - esta na posicao: 3");
  } 
}

Java principios basicos 
