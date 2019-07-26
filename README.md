# CLOCK TIMING USING C
//CONVERT SECONDS  INTO HOURS :MINUTES :SECONDS  FORMATS

#include<stdio.h>
#include<conio.h>
void main()
{
 int h,m,s,n;
 clrscr();
 printf("enter seconds ");
 scanf("%d",&n);

  h=n/3600;
  n=n%3600;
  m=n/60;
  s=n%60;
  printf("Hours=%d ,minutes=%d,seconds=%d ",h,m,s);
  getch();
}
