#include<stdio.h>
#include<conio.h>
void main()
{
int i,j,k,n;
clrscr();
printf("Enter a number");
scanf("%d",&n);
for(i=1;i<=n;i++)
{
for(j=n;j>=i;j--)
printf(" ");
{
for(k=1;k<=i*2-1;k++)
printf("*");
}
printf("\n");
}
getch();
}



