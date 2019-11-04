#include<stdio.h>
int n, k,i,answer=0,a=0,sum=0;
int arr[100000],temp[100000];
void main() 
{
	scanf("%d %d", &n, &k);
	for ( i = 1; i <= n; i++) 
	{
		char bulb;
		scanf(" %c", &bulb);
		if (bulb == 'G') arr[i] = 0;
		if (bulb == 'R') arr[i] = 1;
		if (bulb == 'Y') arr[i] = 2;
        	arr[i]+= sum;
		if ((arr[i] + 1) % 3 == 0)
		{
			temp[i] = 1;
			answer+=1;
			sum+=1;
		}
		else if ((arr[i] + 2) % 3 == 0)
		{
			temp[i] = 2;
			answer += 2;
			sum += 2;
		}
		else temp[i] = 0;
		if (i >= k) sum = sum-temp[++a];
	}
	printf("%d\n", answer);
 

}
