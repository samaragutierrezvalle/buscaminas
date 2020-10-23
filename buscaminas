# buscaminas
package buscaminas;
import java.util.Random;
import java.util.Scanner;
/**
 *
 * @author HP
 */
public class Buscaminas {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
        System.out.println("- Juego de Buscaminas- ");
        //En esta linea de codigo es donde se crea la matriz y fue nuestra compañera  Dominguez Cazales Jennifer Irlanda y Guitierrez Valle Samara
         char[ ][]bom = new  char[5][5]; 
         int x,y;
         for (int i = 0; i < 5; i++) {
             for (int j = 0; j < 5; j++) {
                 bom[i][j]='?';
             }
        }
         //Soto carrion Luis Enrique 
         //El metodo random nos ayudo a darle una posicion a la bomba 
        Random r = new Random();
        x = r.nextInt(5);
        y = r.nextInt(5);
        //Los letreros son adicionales                             // Melgoza Vazquez Lilia Sutsuy
        System.out.println("Crees que este en esta posicion :0  "+(x+1));
        System.out.println("Crees que este en esta posicion O:  "+(y+1));//y aca se le agrega al mas para que el metodo random
        //bom[x][y]='B';                                                //tome del 0 al 4      
      mostrar(bom,true,x,y);
        System.out.println("Fin del juego");
    }
    //ES unn metodo que se llama mostrar nos ayuda ah  mostrar la matriz junto con sus actualizazciones 
   public static void mostrar(char[][] bomb,boolean sal,int xx,int yy){  //Zamora Esparza Yezier Cruz   
                                                                         //Meléndez Mendoza Vicente Angel
       int a, b;
       Scanner leer=new Scanner(System.in);
       
                    for (int x=0; x< bomb.length; x++){
                        for (int y=0; y < bomb.length; y++){
                              System.out.print(" | " + bomb[x][y]+ " | "); 
                             
                          }
                        System.out.println("\n----------------------------------------");
                    }
       if (sal==true) {
           System.out.println("L = sin bomba :)");
       System.out.println("B = con bomba :c ");                 //Ambrocio Perez Michael Haziel
       System.out.println("? = sin destapar");            //Ramírez Alvarado José Armando
           System.out.println("INGRESA LA POSICIPON QUE QUIERES DESTAPAR");
        System.out.println("DONDE A ES LA FILA Y B ES LA COLUMNA");
        System.out.print("INGRESA A --NUMEROS DEL 1 AL 5--");
        a=leer.nextInt()-1;
        System.out.println("_");
        System.out.print("INGRESA B--NUMEROS DEL 1 AL 5--");
        b=leer.nextInt()-1;  //el menos uno porque el usuario ve que es del 1 al 5 y el progama entiende que es del 0 al 4 
       /* if (bomb[a][b]=='?'||bomb[a][b]=='L') {
           bomb[a][b]='L';        //esta parte esta comentada ya que no proporcino el proceso solicitdo 
           mostrar(bomb,sal,xx,yy);
       }*/
        if (a==xx&&b==yy) {
            bomb[a][b]='B';
           mostrar(bomb,sal=false,xx,yy);    //Entre todos 
       }else{
            bomb[a][b]='L';
           mostrar(bomb,sal,xx,yy);
        }
       }
    }
   
         
 //Zamora Esparza Yezier Cruz   +
 //Meléndez Mendoza Vicente Angel+
//Ambrocio Perez Michael Haziel+
//Guitierrez Valle Samara +
//Soto carrion Luis Enrique +
 //Dominguez Cazales Jennifer Irlanda   +
//Melgoza Vazquez Lilia Sutsuy +
//Ramírez Alvarado José Armando+

}
