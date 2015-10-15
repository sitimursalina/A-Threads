# A-Threads
Company A-request threads features

package ThreadA;

public class ThreadA {

   public static void main (String [] args)
	   {
	   
	   //AT-threads request for company A
	   CompAThread AT = new CompAThread ();
	   AT.start ();
	      for (int t = 0; t < 50; t++)
	           System.out.println ("t = " + t + ", t * t = " + t * t);
	   }
	   
	   public void run ()
	   {
	   
	   
	   
	   
	   	      }
	   }
	}

