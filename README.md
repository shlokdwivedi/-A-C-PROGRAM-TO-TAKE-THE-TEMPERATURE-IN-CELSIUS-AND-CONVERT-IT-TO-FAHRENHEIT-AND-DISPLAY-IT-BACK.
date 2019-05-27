# -A-C-PROGRAM-TO-TAKE-THE-TEMPERATURE-IN-CELSIUS-AND-CONVERT-IT-TO-FAHRENHEIT-AND-DISPLAY-IT-BACK.
#include 
 int main() 
{ 
 //Celsius = 5 * (Fahrenheit - 32)/9
float f = 0;
float c = 0;
printf ("enter the values to be converted (fahrenheit) :");
scanf("%f",&f);
c = 5*(f-32)/9 ;
printf("the value converted into celsius is  = %f " , c );
}
