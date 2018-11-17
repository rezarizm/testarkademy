# testarkademy
#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int n;
int m;
int p;
int q;
int r;
int s;

int segitiga(void)
{  system ("cls");
	for(n=0;n<2*m-1;n++)	
	{ printf("*");
		}	
   printf("\n");
   r = m;
   
   for (s=1;s<m;s++)
   {  for (p=0; p<s; p++)
   		{printf(" ");}
   	printf("*");
   	   for (q=0;q<r*2-5;q++)
   	   {printf(" ");}
   	   
   	if ( s == m-1) { printf("\n") ;}
   	else {printf("*\n");}
   	r=r-1;
   }
	
}

int main ()
{ 
printf ("Masukan Tinggi Segitiganya: ");
		scanf ("%d", &m);
		segitiga();
return 0;
}





