# LiteFeeder
LiteFeeder is a extension to [LiteSolder](https://github.com/Carinalo93/LiteSolder) and [LitePlacer](https://github.com/jkuusama/LitePlacer-DEV). - Its a simple platform to start you PCBs fabrication right from your desk, without spending thousands of dollars.

The LiteFeeder is an automatic SMT part feeder for standard 8mm tapes. It comes with a strong magnet and a powerrail to simply mount and exchange the feeder in front of the LitePlacer. Its driven by a cheap stepper motor. The main working principle is very simple. When the LitePlacer picks a part from the LiteFeeder. The Feeder can recognize this in two ways. We used a light barrier to detect the nozzle. Futhermore in the pcb is a place for an hall sensor too. We just used the light barrier but it can be extend to both sensors by default. After detecting the nozzle the LitePlacer wait 6 seconds.After it the stepper pulls the masking tape until the next hole is detected. Thats it its. Simple but powerfull! 

**Bill of materials**
1x 28byj-48 Stepper Motor
1x 30x4mm Neodym Magnet
1x Red 90° right angled SMD LED
1x Green 90° right angled SMD LED
1x Right angled push switch KSS231G
1x ATtiny84 SOIC 14
1x ULN2003A SOIC 16
1x QRE1113 light barrier oder DRV5023 for nozzle dection
1x SX1106 fork light barrier for hole dection
1x JST B5B XH A Connector for the stepper
1x 9155 AVX 2 Pin Battery Connector
2x 3,5x16 Screws 

Some standard 0603 resistors, pinheader and condensators i.e. 10k or 330

* 3D parts
Housing:

[.stl]() [.step]() [.ipt]()

Pulling Wheel:

[.stl]() [.step]() [.ipt]()

Powerrail: (from a pcb coppe plate)

[.step]() [.ipt]()


**PCB**
We've orded the PCB at PCBway.com its really cheap an fast.
*Please Note*: the wiring diagram is fine but there are some issues with the boardlayout. Please verify it. --> You should add an 0.1µ condensator between VCC and GND otherwise it will not work fine. Futhermore the footprint of the battery connector to the powerrail must be integrated. In the gerber file is the battery footprint integrated but not the 0.1µ capacitor. 

[PCB Parts & Files]()







