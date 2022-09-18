# Money-for-No.-of-subjects-passed

#include <stdio.h>

int main() {

int a;
   printf("In how many sub you got passing marks\n");
   printf("enter 1 if pass in maths\n");
   printf("enter 2 if pass in science\n");
   printf("enter 3 if pass in both\n");
   scanf("%d", &a);
   if (a==1||a==2){
      printf("congratulations you got Rs.15");
   }
   else if(a==3){
      printf("congratulations you got Rs.45");
   }
   
   
   
   return 0;
}
