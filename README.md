#include<stdio.h>
void main()
{
  int marks;
  char grade;
  printf("Enter the marks of a student \n");
  scanf("%d",marks);
  
  if(marks>84 && marks<=100)
     grade='A';
  else if(marks>=70 && marks<=84)
     grade='B';
 else if(marks>=55 && marks<=69)
    grade='C';
 else if(marks>=40 && marks<=54)
    grade='D';
 else
    grade='F';
    
 printf("The grade is %c",grade);
} 
 
