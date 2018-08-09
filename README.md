# train-casestudyCoding:
package trichytrains;
public class Trichytrains {
 public static void main(String[] args) {
 String[] depTimes={"6.04","9.04","12.04","15.04","19.04","6.04","9.04",
 "12.04","15.04","19.04","6.04","9.04","12.04","15.04",
 "19.04"};
 int[] passengers={22,119,64,177,21,22,111,87,193,22,11,107,93,162,42};
 //1.display the data
 System.out.println("Chennai to trichy service");
 System.out.println("Day\tTime\tpassengers");
 String day="";
 for(int i=0;i<15;i++){
 //find out the day
 if(i>=0&&i<5)
 day="Monday";
 if(i>=5 && i<10)
 day="Tuesday";
 if(i>11&&i<16)
 day="Wednesday";
 //display information
 System.out.println(day+"\t"+depTimes[i]+"\t"+passengers[i]);
 break;
 }
 }
}
case 2:
 //most popular train
 int max =passengers[0];
 int min = passengers[0];
 int index1=0;
 int index2=0;
for(int i=0;passengers[i].length,i++){
 if(passengers[i]>max){
 max=passengers[i];
 index1=i;
}
if(passengers[i]<min){
min=passengers[i];
index2=i;
}
}
System.out.println("index position of most popular train :"+index1);
System.out.println("most popular train");
System.out.println(day"\t"deptimes+"\t"day+"\t"deptimes[index1]);
System.out.println("least popular train");
System.out.println(day"\t"deptimes+"\t"day+"\t"deptimes[index2]);
//6.04 train is more popular then 9.04 train
System.out.println("deptimes:6.04""\n"day:monday"\t"passengers:22"\n\n"day:Tuesday
"\t"passengers:22"\n"day:wednesday"\t"passengers:11);
System.out.println("deptimes:9.04""\n"day:monday"\t"passengers:119"\n\n"day:tuesday
"\t"passengers:111"\n"day:wednesday"\t"passengers:107);
double p =6.04,q =9.04;
double c11=22,c12=22,c13=11,c21=119,c22=111,c23=107;if(c11>c21&&c11>c22&&c11>c23&&c12>c21&&c12>c22&&c12>c23&&c13>c21&&c13>c22&&c13&&c2
3);
{
System.out.println("6.04 train is popular");
}
else
{
System.out.println("9.04 train is popular");
}
//6.04 train on monday is more popular than the6.04 train on tuesday
if(passengers[0][0]>passengers[0][1]){
system.out.println("6.04 train on monday is more popular");
}
else{
System.out.println("6.04 train on tuesday is more popular");
} 
//display day and train with passsengers below 50
index=0;
for(int passengers[i]=0;passengers[i]<50,passengers[i]++)
{
index=passengers[i];
System.out.println(day"\t "depTimes+day+"\t"depTimes[index]);
}
//average number of passengers travelled on 12.04 train
int index passengers=0;
depTimes[i]="12.04";
index passengers=depTimes[i];
System.out.println("s="+passengers[index [i]);
//list of all trains where passanger number were below 50int passengers[]={22,119,64,177,21,22,111,87,193,22,11,107,93,162,42};
double depTimes[o]={"6.04","9.04","12.04","15.04","19.04"};
double depTimes[1]={"6.04","9.04", "12.04","15.04","19.04"};
double depTimes[2]={"6.04","9.04","12.04","15.04","19.04"};
String e1[]=new string[3];
day[0]="monday";
day[1]="tuesday";
day[3]="wednesday";
for(int i=0;i<3;i++){
for(int j=0;j<5;j++){
if(passengers[j]=50){
System.out.println("day:"+dau[i]+"\ndepTimes:"+depTimes[0]+"\npassengers:"
passengers:"+passengeres[j]");
}
else if(passengers[j]<50)
{
System.out.println("day:"+day[i]+"\ndepTimes:"+deptimes[1]+"\npassengers:"
passengers:"+passengers[j]");}
else if(passengers[j]<50)
{
System.out.println("day:"+day[i]+"\ndepTimes:"+deptimes[1]+"\npassengers:"
passengers:"+passengers[j]");
}
}
}
//the average number of passanger traveling on the 12.04 train over three days
int g, y=64,m=87,n=93,d;
System.out.println("monday\n\t passangers:64\n tuesday\n\tpassangers:87\n\tpassanger"
+ "\n\t passanger:93");d=y+m+n;
System.out.println("The average passangers:"+d/3);
//the average num of passanger where day and is specified by user
int passengers[]={22,119,64,177,21,22,111,87,193,22,11,107,93,162,42};
double depTimes[o]={"6.04","9.04","12.04","15.04","19.04"};
double depTimes[1]={"6.04","9.04", "12.04","15.04","19.04"};
double depTimes[2]={"6.04","9.04","12.04","15.04","19.04"};
String e1[]=new string[3];
day[0]="monday";
day[1]="tuesday";
day[3]="wednesday";
String nm1;
int sum11=0,sum 11=0;sum12=0,total1;
double oi11;
System.out.println(("enter the day");
System.out.println("enter the time");
for(intj=0;j<=5;j++)
{
if(nm1.contentequal(ipl1[0]))
{
if(oi11==oi11[j])
{
System.out.println("The average passanger:ty13[13];");
}}
else if(nm1.contentequals(ipll[1]))
{
if(oi11==oi12[j]){
System.out.println("the average passangers+ty12[j]");
}}}//quit
system.exit(0);
default:
system.out.println("\n invalid!!");
}}}
