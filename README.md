import java.util.Scanner;
public class VoterAge {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int age ;
		Scanner a = new Scanner(System.in);
		System.out.println("Enter the age of the voter:");
		
		age = a.nextInt();
		if(age>=18)
		{
			System.out.println("eligible to vote");
		}
		else
		{
			System.out.println("not eligible to vote");
		}

	}

}
