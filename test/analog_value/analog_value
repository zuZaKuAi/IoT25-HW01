const int potPin = 34;
const int ledPin = 4;

int potValue = 0;


void setup() {
  Serial.begin(115200);
  delay(1000);
  pinMode(ledPin, OUTPUT);
}

void loop() {
  potValue = analogRead(potPin);
  Serial.println(potValue);
  
  analogWrite(ledPin, potValue);
  delay(100);
}
