# Transistors  
>by Dhruv Mahajan

There are two types of transistors which exist in the fascinating world of electronics:
* Current controlled 
  * This includes PNP and NPN.
* Voltage controlled
  * This includes JFET and MOSFET.

Let us begin with the PNP transistor. It is regarded as a 2-junction-3-segment device. Essentially, the two junctions are made of a semiconductor material of choice.
The three parts of the transistors are the emitter, collector and the base.  

  ["Diagram for parts"](https://th.bing.com/th/id/R.22018b78241bb72dfd11e0e10e5853cb?rik=b0ODfcU2hgNrHg&riu=http%3a%2f%2f2.bp.blogspot.com%2f_-_aMTMho2zE%2fTUcOZD2KiXI%2fAAAAAAAAAUM%2f9-6SVH2JoTc%2fs1600%2f1.JPG&ehk=H1R56Os%2fnBwsKWVzUhp6IfpfDTbs0Zew%2bj6jQl9wZLU%3d&risl=&pid=ImgRaw&r=0)

## NPN 
> The functionality, structure and so on of NPN and PNP transistors are basically the same— They simply have inverted polarities. Thus we can simply employ NPN, as it is more commonly used and mass-produced. Let us delve into the various configurations available for utility.
#### Common-Base Configuration:
The Emitter is heavily doped (N-Type) and moderately sized. The Base is lightly doped (P-Type) and is small insize. The Collector (N-Type) is moderately doped and on the larger end.
The Emitter and Base (*forward biased, generally) and the Collector and Base (reverse biased, generally*) form the two junctions.
As the emitter is forward biased, we see the majority charge carriers (electrons) from the emitter go to the base. Here, a few electrons recombine, which results in the production of Base Current, whose value is practically negligible. The electrons from the Emitter now make their way to the Collector, as they are minority carriers in the Base. Since this condition falls under the label of *reverse bias*, the resistance is high, so even though the current flowing is nearly the same as the previous condition, the resistance is very high. Thus, the voltage increases without any practical change in current (theoretically, there is very less change). Ergo, the minimal input becomes amplified. This configuration is called the common-base configuration. Also, the current flows opposite to the direction of the electrons. Hence, IE=IC+IB.

["Common base"](https://circuitglobe.com/wp-content/uploads/2017/05/common-base-connection-npn-transistor.jpg)

#### Common-Emitter Configuration: