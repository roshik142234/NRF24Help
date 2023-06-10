Hello everyone!
I have some exposure to Arduino and I am trying to progress my abilities in this area. I have recently taken up on using the nrf24l01+PA+LNA and the adapter breakout board with a 3.3v regulator modules on my custom arduino car. The problem I am having is that my modules will not communicate with my boards(2 clone r3s and original nano every). I have been mainly using Robin2’s demo tutorial(https://forum.arduino.cc/t/simple-nrf24l01-2-4ghz-transceiver-demo/405123
). His communication checker sketch(post 30) outputs as 0x00 for all values on all three of my modules no matter which board I am using. I double checked and triple checked my wiring. I have also tried many different ways of providing stable supply of power to the modules: I have hooked them up to the 3.3v and 5v pins on my boards, used an external power supply and hooked it up to a wall mount and used both the 3.3v lines and the 5v lines, and I have tried adding decoupling capacitors to each one of these options, and it still does not communicate with my boards. I am using 10 uf capacitors and I don't have a soldering kit nor do I know how to use it, so I have been wiring my power onto a breadboard and connected it to a capacitor on the same breadboard. I then connect wires from that same capacitor to my radio modules. This is all done in the same connected row on the breadboard with the capacitor in the middle. I have tried using the latest and 1.1.7 version of the Nrf24 library by TMRh20. I have also tried using the latest version of the RadioHead library and it is not compatible with the nano every so I have hooked my modules up with my two r3 clones. It just outputs init failed when I wire it up as instructed on many tutorials and running the sample server and client example codes provided. All the tutorials I can find are extremely outdated and I am struggling to get these working. Please help me out!
Thanks!
Hardware Links:
Radio Modules and Adapter Boards: https://www.amazon.com/MakerFocus-NRF24L01-Wireless-Transceiver-Regulator/dp/B08LSPZHT8
Elegoo Clone:
https://www.amazon.com/EL-KIT-001-Project-Complete-Starter-Tutorial/dp/B01CZTLHGE/
Kuman Clone:
http://www.kumantech.com/kuman-project-complete-starter-kit-with-tutorial-for-arduino-uno-r3-mega-2560-robot-nano-breadboard-k4_p0016.html
Arduino Nano Every:
https://www.amazon.com/Arduino-Nano-Every-headers-Mounted/dp/B07WWK29XF/
Software and Tutorials:
I am using the latest Version of Arduino IDE
Robin2 CheckConnection.ino:
https://forum.arduino.cc/t/simple-nrf24l01-2-4ghz-transceiver-demo/405123/30
DroneBotWorkshop: https://www.youtube.com/watch?v=lhGXAJj8rJw&t
One of the many tutorial articles: https://howtomechatronics.com/tutorials/arduino/arduino-wireless-communication-nrf24l01-tutorial/

