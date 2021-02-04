# Vaja7-PWM-STM32F4

2.
 b) Prvi kanal aktivirajte kot PWM Generation CH1. Kateri pin ste omogočili? _____PE9_____. 
 Kaj se izpiše poleg pina? _____TIM1_CH1_____.
 
 d) Koliko je vrednost Perscaler (namig; delitelj) ? ________16________.
 
 e) Koliko znaša sedaj? _____10_____kHz.
 
 3.
  b) Poiščite prenastavljeni parameter Pulse (ki je 50) v vaši kodi in prepišite ukaz, ki ga je generiral CubeMX:
  _____________sConfigOC.Pulse = 50_______________.
  
  5.
   a) V kodi spremenite vrednost širine pulza na 25 %. Zapišite popravljeni ukaz v kodi:
   ___________________sConfigOC.Pulse = 25___________________ . 
   
   Zapišite kaj počnejo ukazi v  1.,2. in 3. vrstici (v user code begin 3):
   _______1. vrstica: Nastavi spremenljivko dutyCycle za duty cycle.______
   _______2. vrstica: Spremenljivki dutyCycle prišteje 10.______
   _______3. vrstica: Če spremenljivka dutyCycle preseže 90, jo ponastavi na 10______
   
   Komentar: Osciloskop je preprosto nastaviti in odčitati podatke iz njega.
             Paziti je potrebno, da pravilno nastavimo vse parametre v STM32CubeIDE, da 
             dobimo pravi signal...
   

 

  
 
 
