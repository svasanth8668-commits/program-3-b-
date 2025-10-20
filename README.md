# program-3-b-
C module 3

EX NO:3-b) Check whether the given number is a armstrong number or not.

Date:19/10/2025 
Name: VASANTH S 
Ref no: 25017538

AIM:
To write a C program to check whether a given number is a armstrong number or not.

ALOGRITHM:
1) Get a number as input from the user.
2) Check whether the number is armstrong or not by using looping statements.
3) print the result using printf() function.

PROGRAM:
```
#include<stdio.h>
#include<math.h>
int main()
{
    int num,org,n=0,sum=0;
    scanf("%d",&num);
    org=num;
    for(int i=num;i!=0;i/=10)
    {
     n++;   
    }
    for(int i=num;i!=0;i/=10)
    {
       sum+=pow(num%10,n); 
    }
    if(sum==org)
    printf("%d is a armstrong number",org);
    else
    printf("%d is not a armstrong number",org);
    
}
```

OUTPUT:
<img width="729" height="135" alt="Screenshot 2025-10-20 102944" src="https://github.com/user-attachments/assets/0f6ed030-6a03-48ad-bf3f-672d88139a46" />

RESULT:
Thus the C program to check whether the given number is a armstrong number of not is executed successfully.







