# DJACM_Tanvi
Tech task Arduino
![image](https://github.com/thetanvi18/DJACM_Tanvi/assets/142569541/6597bc35-0d42-4587-a53c-f2e71d0f7a19)
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{ 
  //turn the LED on(high voltage level)
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  //turn the LED off(low voltage level)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
