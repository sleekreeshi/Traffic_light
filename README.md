# Traffic_light
A project based on working of traffic lights using Arduino UNO board.


This simple little project uses an Arduino and some LEDs to replicate a traffic light. It uses code as an internal timer and continues to run until you cut the Arduino's power supply.


MATERIAL REQUIRED 
(TRAFFIC LIGHT)



•	Bread Board

 
•	3 LEDs (Red, Yellow, Green)

 
•	Resistors 

 
•	Arduino UNO and connection cord 

 
•	Jumper wires 


CODE
ARDUNINO IDE
TRAFFIC LIGHT

SELECT THE BOARD:ARDUINO UNO 
AND PORT NAME

{
Void setup()
 pinMode (8,OUTPUT);   //red
pinMode (10, OUTPUT);   //yellow
pinMode(12, Output);   //green
}

void loop(){

digitalWrite (8,HIGH);   //turn on red for 3 sec
delay (3000);
digitalWrite(10,HIGH);   //turn on yellow for 1 sec
delay (1000);

digitalWrite(8, LOW);   //turn off red
digitalWrite(10,LOW);   //turn off yellow

digitalWrite(12,HIGH);   //turn on green for 3 sec
delay(3000);
diigitalWrite(12,LOW);   //turn off green
delay (500);

digitalWrite(12,HIGH);   //turn on green for 0.5 seconds
delay(500);
digitalWrite(12,LOW);   
delay(500);

digitalWrite(12,HIGH);   //turn on green for 0.5 seconds
delay(500);
digitalWrite(12,LOW);   
delay(500);

digitalWrite(12,HIGH);   //turn on green for 0.5 seconds
delay(500);
digitalWrite(12,LOW);   
delay(1000);


AFTER THE CODE:
CLICK ON COMPILE AND UPLOAD 



