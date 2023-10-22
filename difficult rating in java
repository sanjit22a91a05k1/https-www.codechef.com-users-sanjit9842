/* package codechef; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
	    Scanner s=new Scanner(System.in);
		int t=s.nextInt();
		for(int i=0;i<t;i++)
		{
		    int n=s.nextInt();
		    int a[] =new int[n];
		    for(int j=0;j<n;j++)
		     a[j]=s.nextInt();
		     int c=0;
		     for(int k=1;k<n;k++)
		     {
		         if(a[k]>=a[k-1])
		         {
		         c++;
		         }
		         else
		         {
		         c=0;
		         break;
	
		         }
		     }
		     if(c==0)
		     System.out.println("No");
		     else
		     System.out.println("Yes");
		}
	}
}
