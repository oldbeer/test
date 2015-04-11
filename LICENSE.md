public class HelloWorldApp {

	public static void main(String[] args) {
		System.out.println("Hello World!");

	}

}





#include "stdio.h"
void main(){
int max(int a,int b);

	{if (a>=b)
 return a;
	}
	else
	{return b;
	}

    main()
    int a=1,b=2,c=3,d=4;
    result1=max(a,b,c,d);
    result2=max(a,b,c);
    result=result1+result2;
    printf("sum=%d\n",result);
    return 0;
    
}




public class git {
	 
	 public static void main(String[] args) {
	 String q = "How are you";
         String[] aa=(String[]) q.split(" ");
	 for(int i = aa.length ;i>0 ;i--){
	 System.out.print(aa[i-1]+" ");
	 }
	 }
	}
	
	
	
	
	
import java.awt.Frame;
import java.awt.Label;
import java.awt.event.MouseMotionAdapter;

public class yidong {//在主窗口中移动hello world
	public static void main(String[] args) {
		Frame jf=new Frame("杨彰平");
		jf.setBounds(100, 100, 400, 300);
		final Label j1=new Label("Hello World");
		j1.addMouseMotionListener(new MouseMotionAdapter() {
			public void mouseDragged(java.awt.event.MouseEvent e) { 
				j1.setLocation(e.getX() , e.getY()); 
			} 
		}); 
		jf.add(j1);
		j1.setVisible(true);
		jf.setVisible(true); 
	}

}
