# Electricity-bill-unit-price-calculator
import java.util.Scanner ;
class ElectricityBill   
{
	public static void main(String[] args) 
	{
		Scanner s = new Scanner(System.in);
		System.out.println("Enter Your Electricity Unit");
		
		int unit = s.nextInt();

		if (unit >0 && unit <50)
		{
			double rs= unit*2.65;
			System.out.println(rs);
		}
		else if (unit>51 && unit <100)
		{
			double rs= unit*3.35;
			System.out.println(rs);
		}
		else if (unit>101 && unit <200)
		{
			double rs= unit*5.40;
			System.out.println(rs);
		}
		else if (unit >201 && unit <300)
		{
			double rs= unit*7.10;

			System.out.println(rs);
		}
		else if (unit>301 && unit <400)
		{
			double rs= unit*7.95;
			System.out.println(rs);
		}
		else if (unit>401 && unit<500)
		{
			double rs=unit*8.50;
			System.out.println(rs);
		}
		else if (unit>501)
		{
			double rs= unit*9.95;
			System.out.println(rs);
		}
		else
		{
			System.out.println("Please Visit MSEDCL");
		}
		
		
	}
}
