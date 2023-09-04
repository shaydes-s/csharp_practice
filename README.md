# csharp_practice
unit 1a lab
using System;
					
public class Program
{
	public static void Main()
	{
		Console.WriteLine("Hello World");
		//not touching any of the default code cause I don't know how to set it up
		//defining first variables
		int X = 2;
		string Name = "Shayln";
		
		//printing my name and converting the int to a string to print
		Console.WriteLine(Name);
		string Value = Convert.ToString(X);
		Console.Write(Value);
		
		//more variables to play with
		int Y;
		Y = 42;
		bool f = false;
		char myChar = 's';
		double myNum = 24.1;
		
		//converting ints to strings and printing everything
		string myCharStr = Convert.ToString(myChar);
		string Value2 = Convert.ToString(Y);
		Console.WriteLine(" " + Value2);
		Console.WriteLine(myNum + myCharStr);
		Console.WriteLine(f);
		
		/*number specific variables to do....
		...math with*/
		int R = 20;
		int W = 5;
		int P = 3;
		int B = 7;
		
		//said math
		int O = (R / W);
		//if statement, even though in my example O isn't gonna suddenly change
		if (O >= P)
		{
			Console.WriteLine("O variable is bigger than P variable");
		}
		else
			Console.WriteLine("O variable is smaller than P variable");
		//more math
		B += 3;
		//printing results of the B math
		string BString = Convert.ToString(B);
		Console.WriteLine(BString);
	}
}
