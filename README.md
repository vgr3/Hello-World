# Hello-World
# Veronica Roth
# Brandon Ferruzza
# Dan Feathers

This is the Hello World project

void setup() {
 
  pinMode(13, OUTPUT);    // sets the digital pin 13 as output
  pinMode(8, INPUT);

}

void loop() {

  //If the reset is pulled down??? then blink 
  if (digitalRead(8) == LOW)
  {
    digitalWrite(13, HIGH); // sets the digital pin 13 on
    delay(1000);            // waits for a second1
    digitalWrite(13, LOW);  // sets the digital pin 13 off
    delay(1000);            // waits for a second 
  }

}
