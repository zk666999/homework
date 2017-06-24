```
void setup() {
 for(int i=2;i<=6;i++){
 pinMode(i,OUTPUT);
 }// put your setup code here, to run once:

}

void loop(){
  digitalWrite(2,HIGH);
   digitalWrite(3,HIGH);
    digitalWrite(4,HIGH);
     digitalWrite(5,HIGH);
      digitalWrite(6,HIGH);
      delay(3000);
  for(int x=2;x<=6;x++){
  digitalWrite(x,LOW);
  delay(300);

  }
  delay(3000);
   for(int x=2;x<=6;x++){
  digitalWrite(x,HIGH);
  delay(300);
   }

digitalWrite(2,LOW);
   digitalWrite(3,LOW);
    digitalWrite(4,LOW);
     digitalWrite(5,LOW);
      digitalWrite(6,LOW);
      delay(3000);
}
```
!["homework1"](https://github.com/zk666999/homework/blob/master/IMG_20170625_013533.jpg)
