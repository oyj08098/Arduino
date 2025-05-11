202234908 오예진
IoT25-HW01

port

![스크린샷 2025-05-12 005849](https://github.com/user-attachments/assets/e988c936-9f22-4381-b278-e489e25e17c9)


code

#include <Arduino.h>

#define LED 2

void setup() {
  // put your setup code here, to run once:
  Serial.begin(115200);
  pinMode(LED, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(LED, HIGH);
  Serial.println("LED is on");
  delay(1000);
  digitalWrite(LED, LOW);
  Serial.println("LED is off");
  delay(1000);
}

![code](https://github.com/user-attachments/assets/899dd3e5-4b12-486f-b9e5-8ebe61d292cc)


video
https://youtube.com/shorts/RTQdYE1Z0yw?feature=share
