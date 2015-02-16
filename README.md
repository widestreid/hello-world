# hello-world
This is the repository I am starting on 2-5-2015

Notes on Arduino 

There is the setup function 
There is the loop function 

the #define directive 
int is a variable type 

Bringing Parameters into the function

When dividing your sketch up into functions it is often useful to think about what service a function could provide. 

Where we define the function at the bottom of the sketch, we have to declare the type of variable in the parameters. 

Global, local, and static variables

Is an Arduino written in "c"?
For programming the microcontroller, the arduino platform provides an IDE based on the Processing project, which includes support for C and C++ programming languages. 

Local Variable X is said to shadow the global variable of the same name. 

In addition to defining parameters, you can also define variables that are not parameters but are just for use within a function. These are called local variables. 

void indicate(int xyz) in this case we are defining paramters "xyz"
local variables are defined in the {} brackets of the function 

pinMode is a function built into the Arduino IDE

Blink different LEDS at different rates with an Arduino? 
