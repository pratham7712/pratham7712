#include <stdio.h>

int main()
{
    int i,j,k,count=1;
    for(i=5;i>=1;i--)
    {
        for(k=1;k<=count;k++)
        {
            printf(" ");
        }
        for(j=1;j<=(i*2)-1;j++)
        {
            printf("*");
        }
        printf("\n");
        count++;
    }
	 count=5;
    for(i=1;i<=5;i++)
    {
        for(k=1;k<=count;k++)
        {
            printf(" ");
        }
        for(j=1;j<=(i*2)-1;j++)
        {
            printf("*");
        }
        printf("\n");
        count--;
    }


    return 0;
}
