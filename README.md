# The-Fibonacci-numbers-
package qu3;

public class QU3 {


	public static void main(String a[]){
        //The first num in fibonacci is 1
    int fibCount = 13;
         int[] feb = new int[fibCount];
            feb[1] = 1;
         for(int i=2; i < fibCount; i++){
            feb[i] = feb[i-1] + feb[i-2];
            //recursive function
         }

         for(int i=1; i< fibCount; i++){
            System.out.print(feb[i] + " ");
         }
	}
}
