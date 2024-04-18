Utilizing Bluetooth modules and an Android application, this cutting-edge system 
operates with a smartphone as its remote control. The HC-05 module acts as the receiver of text format code, transmitted via Bluetooth from the application. The code 
serves as instructions for the microcontroller, processed by the decode circuit after 
being received by the HC-05 module from the smartphone.
To accomplish this, the steps are as follows:
1. Communication via Bluetooth can be facilitated by downloading various apps, 
such as "Bluetooth Terminal HC-05".
2. Connected to your microcontroller or Arduino board, ensure that it is properly.
3. Holding the button until the LED flashes rapidly, power up the module and activate 
pairing mode.
4. Make sure Bluetooth is enabled by checking your smartphone's settings.
5. List HC-05 as your device choice from the available options.
6. "1234" is an option to consider using as a password when prompted. Alternatively, 
you could input any previously established password.
7. Download and launch the Bluetooth terminal app following a successful pairing.
8. From the roster of accessible devices, pick out the module that is matched in pairs.
9. Your smartphone should now be successfully connected.
10. Send the instruction stated in Table 1 by using the app.
Table 3 Commands to perform activities
Action Command
Forward Motor1 ‘M’
Stop Motor 1 ‘m’
5
Forward Motor2 ‘N’
Stop Motor2 ‘n’
Turn Right ‘X’
Turn Left ‘Z’
Relay1 ON/OFF ‘A’
Relay2 ON/OFF ‘B’
Relay3 ON/OFF ‘C’
Relay4 ON/OFF ‘D’
