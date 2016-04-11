# Arduino
//codigo en arduino de sobre el encendido y apagado de un led rojo
// En el pin 13 se conectó el led rojo

int led = 13;
int ledverde=12;  //Se agrego un nuevo led
void setup() {
  // Se inicia el pin como salida
  pinMode(led, OUTPUT);
}

// Se hace un ciclo infinito
void loop() {
  digitalWrite(led, HIGH);  
  delay(500);               
  digitalWrite(led, LOW);   
  delay(1500);              
}
