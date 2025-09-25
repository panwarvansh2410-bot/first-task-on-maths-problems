# first-task-on-maths-problems

// finding percentage obtain by the student


// step 3
                     

# include <stdio.h>

int main() {

    int p = 82;
    int c = 94;
    int m = 76;
    int e = 77;
    int h = 83;

    int sum  = p + c + m + e + h;
    float per = (sum )/500.0 * 100;
    printf("%f" , per);
}    



// step 4 


# include <stdio.h>

int main() {

    int physics  = 82;
    int chemistry  = 94;
    int mathematics = 76;
    int english = 77;
    int hindi = 83;

    int sum= physics + chemistry + mathematics + english + hindi;
    float percentage = (sum)/500.0 *100;
    printf("percentage : %f", percentage);
}  


// step 5

     
# include <stdio.h>

int main() {

    int physics ;
    printf("enter the marks of physics :");
    scanf("%d", &physics);

    int mathematics;
    printf("enter the marks of mathematics :");
    scanf("%d", &mathematics);

    int chemistry ;
    printf("enter the marks of chemistry :");
    scanf("%d", &chemistry);

    int hindi ;
    printf("enter the marks of hindi:");
    scanf("%d", &hindi);

    int english ;
    printf("enter the marks of english :");
    scanf("%d", &english);

    int sum = physics + chemistry + mathematics + english + hindi;
    float percentage = (sum)/500.0 *100;
    printf("percentage of student is : %f", percentage);
     
}
   
  
   
   // step 6
               
   # include <stdio.h>

int main() {

    int physics , chemistry , mathematics , hindi , english, sum;


    printf("enter the marks of physics :");
    scanf("%d", &physics);

    printf("enter the marks of mathematics :");
    scanf("%d", &mathematics);

    printf("enter the marks of chemistry :");
    scanf("%d", &chemistry);

    printf("enter the marks of hindi:");
    scanf("%d", &hindi);

    printf("enter the marks of english :");
    scanf("%d", &english);

    sum = physics + chemistry + mathematics + english + hindi;

    float percentage = (sum)/500.0 *100;
    printf("percentage of student is : %f", percentage);
 
}            



                   // find area and circumference of circle


// step 3
 
# include <stdio.h>

int main() {
    int r= 14 ;
    float a = 3.14*r*r ;
    printf("%f\n", a);

    float c = 2*3.14*r;
    printf("%f\n", c); 

    return 0 ;
}
      



// step 4 
    
# include <stdio.h>
     

int main() {
    int radius = 14 ;
    float area = 3.14*radius*radius ;
    printf("%f\n", area);

    float circumference = 2*3.14*radius;
    printf("%f\n", circumference); 

    return 0 ;
    
}    


// step 5 
    
# include <stdio.h>

int main() {
    int radius ;
    printf("enter the radius of circle :");
    scanf("%d", &radius);

    float area = 3.14*radius*radius;
    printf("area of circle is : %f\n", area);

    float circumference = 2*3.14*radius;
    printf("circumference of circle is : %f\n", circumference);

}  


// step 6
      
# include <stdio.h>

int main() {

    int radius ;
    printf("enter the radius of circle :");
    scanf("%d", &radius);

    float area = 3.14*radius*radius;
    printf("area of circle is : %f\n", area);

    float circumference = 2*3.14*radius;
    printf("circumference of circle is : %f\n", circumference);

}      



                    // for converting celcius to farhenhiet
  
              // step 3
      
# include <stdio.h>
int main(){
    int c = 35 ;
    float f = (c*9/5)+32 ;

    printf("%f", f);
}    


              // step 4
    
              
# include <stdio.h>
int main(){
    int celcius = 35 ;
    float fahrenheit = (celcius*9/5)+32;

    printf("temprature in fahrenheit is : %f", fahrenheit);
}         


                    //step 5
           
    # include <stdio.h>
int main(){
    int celcius;
    printf("enter the temprature in celcius :");
    scanf("%d", &celcius);
    
    float fahrenheit = (celcius*9/5)+32;
    printf("temprature in fahrenheit is : %f ", fahrenheit);

}         


                    //step 6 
              
                    # include <stdio.h>
int main(){
    int celcius;
    printf("enter the temprature in celcius :");
    scanf("%d", &celcius);
    
    float fahrenheit = (celcius*9/5)+32;
    printf("temprature in fahrenheit is : %f ", fahrenheit);

                }      


                           

                    //  for checking two number equal or not

            
                    //step 3 
         
                    
    # include <stdio.h>
int main(){
           
    int a = 5 ;
    int b = 5 ;
    if (a==b) {
        printf("the numbers are equal\n");
    }
        else {
            printf("the numbers are not equal\n");
        }
        return 0 ;
    }    


                // step 4 
       
                
              # include <stdio.h>
int main(){
           
    int firstnum = 5 ;
    int secondnum = 5 ;

    if (firstnum == secondnum) {
        printf("the numbers are equal\n");
    }
        else {
            printf("the numbers are not equal\n");
        }
        return 0 ;
    }      
               
              
               
               // step 5

            # include <stdio.h>
            
int main(){
           
    int firstnum; 
    printf("enter the firstnum : ");
    scanf("%d", &firstnum);

    int secondnum; 
    printf("enter the secondnum :");
    scanf("%d", &secondnum );

    if (firstnum == secondnum){
        printf("the numbers are equal\n");
    }
    else {
        printf(" the numbers are not equal");
    }

}     


             //step 6
    
             # include <stdio.h>
            
int main() {
           
    int firstnum , secondnum ;
    printf("enter the firstnum : ");
    scanf("%d", &firstnum);

    
    printf("enter the secondnum :");
    scanf("%d", &secondnum );

    if (firstnum == secondnum){
        printf("the numbers are equal\n");
    }
    else {
        printf(" the numbers are not equal");
    }
}      



       // find greatest of three numbers

       // step 3

       # include <stdio.h>
            
int main() {

    int a = 56;
    int b = 89;
    int c = 45;
    
    if(a>=b && a>=c) {
        printf("a is greatest\n");
    }

    else if (b>=a &&b>=c) {
        printf("b is greatest\n");
    }
    else {
        printf("c is greatest\n");
    }
     return 0 ;
    }    



          // step 4
 
          # include <stdio.h>
            
int main() {

    int firstnum = 56;
    int secondnum = 89;
    int thirdnum = 45;
    
    if(firstnum>=secondnum && firstnum >=thirdnum) {
        printf("firstnum is greatest\n");
    }

    else if (secondnum>=firstnum && secondnum>=thirdnum) {
        printf("secondnum is greatest\n");
    }
    else {
        printf("thirdnum is greatest\n");
    }
     return 0 ;
} 


           //step 5

        # include <stdio.h>
            
int main() {

    int firstnum ;
    printf("enter the first number:") ;
    scanf("%d", &firstnum);
    
    int secondnum ;
    printf("enter the second number :");
    scanf("%d", &secondnum);

    int thirdnum ;
    printf("enter the third number :");
    scanf("%d", &thirdnum);

    if(firstnum>=secondnum && firstnum >=thirdnum) {
        printf("firstnum is greatest\n");
    }

    else if (secondnum>=firstnum && secondnum>=thirdnum) {
        printf("secondnum is greatest\n");
    }
    else {
        printf("thirdnum is greatest\n");
    }
     return 0 ;

}    


              // step 6
             
            
              
          # include <stdio.h>
            
int main() {

    int firstnum , secondnum , thirdnum ;  

    printf("enter the first number:") ;
    scanf("%d", &firstnum);
    
    
    printf("enter the second number :");
    scanf("%d", &secondnum);

    
    printf("enter the third number :");
    scanf("%d", &thirdnum);

    if(firstnum>=secondnum && firstnum >=thirdnum) {
        printf("firstnum is greatest\n");
    }

    else if (secondnum>=firstnum && secondnum>=thirdnum) {
        printf("secondnum is greatest\n");
    }
    else {
        printf("thirdnum is greatest\n");
    }
     return 0 ;
}
      



           // for checking number is even or odd


           // step 3
         
           # include <stdio.h>
            
int main() {

    int a = 5 ;

    if(a/2==0) {
        printf("the number  is even\n");
    }

    else {
        printf("the number is odd\n");
    }
    return 0 ;
    }    


            // step 4 

     
      # include <stdio.h>
            
int main() {

    int num = 5 ;

    if(num/2==0) {
        printf("the number  is even\n");
    }

    else {
        printf("the number is odd\n");
    }
    return 0 ;
    }       


             // step 5 
      
# include <stdio.h>
            
int main() {

    int num ;
    printf("enter thenumber :");
    scanf("%d", &num);

    if(num/2==0) {
        printf("the number is even\n");
    }
        else {
            printf("the number is odd\n");
        }
        return 0 ;
    }    


            // step 6
  
         # include <stdio.h>
            
int main() {

    int num ;
    printf("enter thenumber :");
    scanf("%d", &num);

    if(num/2==0) {
        printf("the number is even\n");
    }
        else {
            printf("the number is odd\n");
        }
        return 0 ;   
                }     



                // for checking a year is leap year or not

                             // step 3
                
                 # include <stdio.h>
            
int main() {

    int y = 2025;
    if(y/4==0) {
        printf("the year is leap year\n");
    }

    else {
        printf("the year is non leap year ");
    }
    return 0 ;
    }    

            //step 4
                

            # include <stdio.h>
            int main() {

            int year = 2025;
    if(year/4==0) {
        printf("the year is leap year\n");
    }

    else {
        printf("the year is non leap year ");
    }
    return 0 ;
    }      
   
    

                // step 5 
                
        # include <stdio.h>
            int main() {

                int year ; 
                printf("enter the year :");
                scanf("%d", &year);

    if(year/4==0) {
        printf("the year is leap year\n");
    }
    else {
        printf("the year is non leap year ");
    }
    return 0 ;
}       



                // step 6

                
        # include <stdio.h>
            int main() {

                int year ; 
                printf("enter the year :");
                scanf("%d", &year);

    if(year/4==0) {
        printf("the year is leap year\n");
    }
    else {
        printf("the year is non leap year ");
    }
    return 0 ;
}          
            


                 // for swaping of two numbers 

                 // step 3

              # include <stdio.h>
            int main() {

                int a= 5;
                int b = 8 ;
               int  temp ;

                temp = a ;
                a = b ;
                b = temp ;

                printf ("the value of a after swapping : %d\n", a);
                printf ("the value of b after swapping : %d\n", b);


          return 0;      
            }        


                      // step 4 

                     # include <stdio.h>
            int main() {

                int  firstnum = 5;
                int secondnum = 8 ;
               int  temp ;

                temp = firstnum;
                firstnum = secondnum ;
                secondnum = temp ;

                printf ("the value of firstnum after swapping : %d\n", firstnum);
                printf ("the value of secondnum after swapping : %d\n", secondnum);

                return 0 ;

                }        


                        // step 5 

                        # include <stdio.h>
            int main() {

                int firstnum;
                printf("enter the firstnum :");
                scanf("%d", &firstnum);

                int secondnum ;
                printf("enter the secondnum :");
                scanf("%d", &secondnum );

                int temp ;
                temp = firstnum;
                firstnum = secondnum ;
                secondnum = temp;

                printf ("the value of firstnum after swapping : %d\n", firstnum);
                printf ("the value of secondnum after swapping : %d\n", secondnum);

                  return 0 ;
            }    


                 // step 6 

                 # include <stdio.h>
            int main() {

                int firstnum , secondnum ;
                printf("enter the firstnum :");
                scanf("%d", &firstnum);

                
                printf("enter the secondnum :");
                scanf("%d", &secondnum );

                int temp ;
                temp = firstnum;
                firstnum = secondnum ;
                secondnum = temp;

                printf ("the value of firstnum after swapping : %d\n", firstnum);
                printf ("the value of secondnum after swapping : %d\n", secondnum);

                  return 0 ;   }

    
       

              

               // after calculating percentage , find the grade of student

               // step 3 

               # include <stdio.h>

int main() {

    int p = 82;
    int c = 94;
    int m = 76;
    int e = 77;
    int h = 83;

    int sum  = p + c + m + e + h;
    float per = (sum )/500.0 * 100 ;

    if(per>= 90){
        printf("grade A \n");
    }

    if(per>=80 && per<90) {
        printf("grade B \n");
    }

    if(per>=60 && per<80) {
        printf("grade C\n");
    }

    if(per<60) {
        printf("grade D \n");
    }

    return 0 ;

}       

    
                // step 4
     
         # include <stdio.h>

int main() {

    int physics = 82;
    int chemistry = 94;
    int mathematics = 76;
    int english = 77;
    int hindi = 83;

    int sum  = physics + chemistry + mathematics + english + hindi;
    float per = (sum )/500.0 * 100 ;

    if(per>= 90){
        printf("grade A \n");
    }

    if(per>=80 && per<90) {
        printf("grade B \n");
    }

    if(per>=60 && per<80) {
        printf("grade C\n");
    }

    if(per<60) {
        printf("grade D \n");
    }

    return 0 ;

 }   


                 // step 5
                 # include <stdio.h>

int main() {

    int physics ;
    printf("enter the marks of physics :");
    scanf("%d", &physics);

      int mathematics;
    printf("enter the marks of mathematics :");
    scanf("%d", &mathematics);

      int chemistry ;
    printf("enter the marks of chemistry :");
    scanf("%d", &chemistry);

        int hindi ;
    printf("enter the marks of hindi:");
    scanf("%d", &hindi);
    
      int english ;
    printf("enter the marks of english :");
    scanf("%d", &english);


    int sum  = physics + chemistry + mathematics + english + hindi;
    float per = (sum )/500.0 * 100 ;

    if(per>= 90){
        printf("grade A \n");
    }

    if(per>=80 && per<90) {
        printf("grade B \n");
    }

    if(per>=60 && per<80) {
        printf("grade C\n");
    }

    if(per<60) {
        printf("grade D \n");
    }

    return 0 ;
}
    
    
       


             // step 6 

             # include <stdio.h>

int main() {

    int physics, chemistry, mathematics, hindi, english;
    printf("enter the marks of physics :");
    scanf("%d", &physics);

      
    printf("enter the marks of mathematics :");
    scanf("%d", &mathematics);

      
    printf("enter the marks of chemistry :");
    scanf("%d", &chemistry);

        
    printf("enter the marks of hindi:");
    scanf("%d", &hindi);
    
      
    printf("enter the marks of english :");
    scanf("%d", &english);


    int sum  = physics + chemistry + mathematics + english + hindi;
    float per = (sum )/500.0 * 100 ;

    if(per>= 90){
        printf("grade A \n");
    }

    if(per>=80 && per<90) {
        printf("grade B \n");
    }

    if(per>=60 && per<80) {
        printf("grade C\n");
    }

    if(per<60) {
        printf("grade D \n");
    }

    
}     


               // for finding simple interest and compound interest 

               // step 3

            # include <stdio.h>
            # include <math.h>
            int main () {
            
                int p = 7800;
                int r =5;
                int t = 3 ;

                float si = (p*r*t)/100.0;
                printf("%f\n", si);

                float A  =  p * pow(1+ r/100.0 ,t) ;
                printf("%f\n", A);

                float ci = (A - p) ;
                printf("%f", ci);

                return 0 ;
            }    


            // step 4 

            # include <stdio.h>
            # include <math.h>
            int main () {
            
                int principle = 7800;
                int rate =5;
                int time = 3 ;

                float simple  = (principle*rate*time)/100.0;
                printf("%f\n", simple );

                float Amount  =  principle * pow(1+ rate/100.0 ,time) ;
                printf("%f\n", Amount);

                float compound  = (Amount - principle) ;
                printf("%f\n", compound);

                return 0 ;
            }     


                  // step 5 

                  # include <stdio.h>
            # include <math.h>
            int main () {
            
                int principle ;
                printf("enter the principle amount : ");
                scanf("%d" , &principle );

                int rate ;
                printf("enter the rate :");
                scanf("%d", &rate);

                int time ;
                printf("enter the time :");
                scanf("%d", &time);

                float simple  = (principle*rate*time)/100.0;
                printf("%f\n", simple );

                float Amount  =  principle * pow(1+ rate/100.0 ,time) ;
                printf("%f\n", Amount);

                float compound  = (Amount - principle) ;
                printf("%f\n", compound);

                return 0 ;
            }     


                // step 6 

                # include <stdio.h>
            # include <math.h>
            int main () {
            
                int principle,rate,time ;
                printf("enter the principle amount : ");
                scanf("%d" , &principle );

                
                printf("enter the rate :");
                scanf("%d", &rate);

            
                printf("enter the time :");
                scanf("%d", &time);

                float simple  = (principle*rate*time)/100.0;
                printf("%f\n", simple );

                float Amount  =  principle * pow(1+ rate/100.0 ,time) ;
                printf("%f\n", Amount);

                float compound  = (Amount - principle) ;
                printf("%f\n", compound);

                return 0 ;
            }     

                



            

                
                




            

                
                


                
        
    

        
    


    


    


    
       

    

       
