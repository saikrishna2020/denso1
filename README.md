#include <stdio.h>
int main()
{
int n,i,p,count=1;
scanf("%d%d",&n,&p);
while(n>=1)
{
    i=n-n*(p*0.01);
    n=i;
    count++;
}
printf("%d",count);
return 0;
}
