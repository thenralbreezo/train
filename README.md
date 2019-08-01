# train
package train;
import.java.util.*;
public class Train{


public static void main(string[]args){
Scanner sc=new Scanner(System.in);
String[]day={"Monday","Monday","Monday","Monday","Monday","Tuesday","Tuesday","Tuesday","Tuesday","Tuesday","Wednesday","Wednesday","Wednesday","Wednesday","Wednesday",}
double[]time={06.04,09.04,12.04,15.04,19.04,06.04,09.04,12.04,15.04,19.04,06.04,09.04,12.04,15.04,19.04};
int[]passenger={22,119,64,177,21,22,111,87,193,22,11,107,93,162,42};

System.out.println("\nDays\t\t\tDeparturetime\t\t\tPassenger number");
for(int i=0;i<5;i++)
System.out.println(day[i]+"\t\t\t"+time[i]+"\t\t\t"+passenger[i]);

System.out.println("\nDays\t\t\tDeparturetime\t\t\tPassenger number");
for(int i=5;i<10;i++)
System.out.println(day[i]+"\t\t\t"+time[i]+"\t\t\t"+passenger[i]);


System.out.println("\nDays\t\t\tDeparturetime\t\t\tPassenger number");
for(int i=10;i<15;i++)
System.out.println(day[i]+"\t\t\t"+time[i]+"\t\t\t"+passenger[i]);


int most=passenger[0];
int inp=0;
for(int i=0;i<15;i++){
if(passenger[i]>most){
most=passenger[i];
inp=i;
}
}
System.out.println("\nThe most popular train:"+day[inp]+"\t\t\t"+time[inp]);


int least=passenger[0];
int inp=0;
for(int i=0;i<15;i++){
if(passenger[i]>least){
least=passenger[i];
inp=i;
}
}
System.out.println("\nThe least popular train:"+day[inp]+"\t\t\t"+time[inp]);


int train
1=(passenger[0]+passenger[5]+passenger[10])/3;
int train
2=(passenger[1]+passenger[6]+passenger[11])/3;


if(train1>train2)
System.out.println("\n6.04 train is more popular than 9.04 train");
else
System.out.println("\n9.04 train is more popular than 6.04 train");

if(passenger[0]>passenger[5])
System.out.println("\n6.04 train on monday is  more popular than 6.04 train on tuesday");
else
System.out.println("\n6.04 train on monday is not more popular than 6.04 train on tuesday");

for(int i=0;i<15;i++){
if(passenger[i]<50){
System.out.println("("+day[i]+","+time[i]+")");
}
}

int average=(passenger[2]+passenger[7]+passenger[12])/3;
System.out.println("\n\tAverage number of passenger travelling on the 12.04 train:"+average):

}
}









