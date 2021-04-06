# include  < Servo.h >

Servo motor;

int deger;
int derece;

geçersiz  kurulum () {
  motor. eklemek ( 3 );

}

geçersiz  döngü () {

  deger = analogRead (A0);
  derece = harita (deger, 0 , 1023 , 0 , 180 );
  motor. yazmak (derece);

}
