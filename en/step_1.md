The Raspberry Pi computer has a number of General Purpose Input/Output pins, that can be used to interact with electronic components. You can learn more about them by looking at [this resource](../../rpi-gpio-pins){:target="_blank"}.

LED stands for Light Emitting Diode. It is an electronic components that emits light current flows through it. The **diode** part of the name tells us that it will only conduct electricity in one direction, so you need to be careful how you connect them to your circuits.

You need to use a resistor when wiring an LED to a Raspberry Pi, to make sure the LED doesn't blow. You can find out how to work out which resistor to use by looking at [this resource](../generic-physical-led-calcs){:target="_blank"}.

- To connect and LED to the resistor, place the LED and resistor in series with each other. You can use a breadboard to do this, use jumper leads, or solder them. It doesn't matter which leg of the LED the resistor is connected to.

	![breadboard](images/breadboard.jpg)
	![jumper](images/jumper.jpg)
	![solder](images/solder.jpg)

- Once the LED and resistor are in series with each other, you can use jumper leads to connect the circuit to the Raspberry Pi. The long leg of the LED should connect to a numbered GPIO pin and the short leg to a GND pin, as shown in the two diagrams below.

	![led1](images/led1.png)
	![led2](images/led2.png)

- If you want to test that your LED is working correctly, before programming it to turn on, you can connect it directly to the 3.3V pin on the Raspberry Pi

	![led3](images/led3.png)



