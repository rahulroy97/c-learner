#include <stdio.h>
#include <conio.h>

int main() {

int i,j,limit;

printf("enter the limit you want to print : ");
scanf("%d", &limit);

for ( i = 1, i <= limit, i++) {

for ( j = 1, j <= i, j++) {

printf("%d",j);
}

printf("\n");
}
getch();
return 0;
}
