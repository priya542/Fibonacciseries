# Fibonacciseries
writing fibonaccii series using java code

public class Fibonacciseries {

	public static void main(String[] args) {
		int a=0,b=1,i,c;
		System.out.println(a + "" + b);
		for(i=1;i<=10;i++) {
			c=a+b;
			System.out.println("" + c);
			a=b;
			b=c;
			
		}
		
		

	}

}

