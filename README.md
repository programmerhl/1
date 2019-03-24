# 1
次方的后三位
#include<stdio.h>
void main()
{
 int i,x,y,z=1;
 printf("input x y\n");
 scanf("%d%d",&x,&y);
 for(i=1;i<=y;i++)
	 z=z*x%1000;
  if(z>=1000)
  {
    printf("%d\n",z);
  }
  else
  {
    printf("%d\n",z);
  }


}
