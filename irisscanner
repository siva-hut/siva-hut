import java.util.*;
import java.io.*;
public class irisscanner {
	public static void main(String args[]) throws IOException
	{	//predefined array of unique values
		List<String> uniquecd = Arrays.asList("12345", "48939", "09355", "99484", "80974", "94294", "89074", "89594","58743","34094");
		File file = new File("D:\\Irisscanner");
		try {
			BufferedReader br = new BufferedReader(new FileReader(file));
			String st;
			 while ((st = br.readLine()) != null)
			 {	String tokens[] = st.split(", ");
			 	for(int i=0;i<tokens.length;i++)
			 	{
			 		System.out.print(tokens[i]);
			 		if(uniquecd.contains(tokens[i]))
			 		{
			 			System.out.print(" : unique code accessed \n");
			 		}
			 		else
			 			System.out.print(" : unique code not accessed \n");
			 	}
			  
			 }
			 
			
		} catch (FileNotFoundException e) {
			
			e.printStackTrace();
		}
	}
}
