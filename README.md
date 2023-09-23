# Matrix Button Keyboard
![Preview](https://github.com/yasenOfficial/MatrixButtonKeyboard/blob/main/images/keyboardmatrix.png)


# Introduction
Welcome to the Matrix Keyboard PCB project. This printed circuit board (PCB) is designed for building a matrix keyboard using diodes and buttons. The PCB is compatible with an Arduino Pro Micro, making it an ideal choice for various projects that require user input through buttons. Whether you are working on a custom keyboard, a control panel, or any other interactive application, this PCB simplifies the process.

# Features
Matrix Keyboard Design: This PCB is designed to create a matrix keyboard, allowing you to connect multiple buttons efficiently and reduce the number of required input pins on your microcontroller.

# Diode Integration: 
1N4148 Diodes are included to prevent ghosting and ensure accurate keypress detection in the matrix.

# Arduino Pro Micro Compatibility:
he PCB is designed to work seamlessly with the Arduino Pro Micro, making it easy to program it to simulate button key presses.

## Components
To assemble the Matrix Keyboard PCB, you will need the following components:

Matrix Keyboard PCB
Buttons (momentary switches)
Diodes (1N4148 or similar)
Arduino Pro Micro
Soldering iron and solder
Connecting wires (for Arduino Pro Micro)

## PCB
This is a preview of the PCB: </br>
![PCB](https://github.com/yasenOfficial/MatrixButtonKeyboard/blob/main/images/keyboardmatrixpcb.png)

## Schematic
This is the schematic:
![Schematic](https://github.com/yasenOfficial/MatrixButtonKeyboard/blob/main/images/keyboardmatrixschematic.png)


## First Prototype
This is a simple prototype using a breadboard ( 1 column, 4 rows ) I have also written some test code for it

![Prortype](https://github.com/yasenOfficial/MatrixButtonKeyboard/blob/main/images/firstprototype.png)

## Assembly Instructions
Solder Diodes: Start by soldering the diodes onto the PCB. Each button should have a diode in series with it to prevent ghosting. Check the schematic to see how to wire them in detail

Solder Buttons: Insert and solder the momentary buttons into the PCB. Align them with the button footprints on the PCB, making sure the buttons sit flush against the PCB.

Connect to Arduino: Using connecting wires, establish connections between the PCB and the Arduino Pro Micro. Connect each row and column to a unique digital or analog pin on the Pro Micro. Make a note of the pin assignments for programming.

Upload Code: Write or find Arduino code for your specific project. Use the pin assignments to configure the matrix in the code. Upload the code to the Arduino Pro Micro.

### Test: 
Test the matrix keyboard to ensure all buttons register correctly. If any keys are not working as expected, check your soldering and wiring connections.

#### Contributing
If you have ideas for improvements, modifications, or additional features for this Matrix Keyboard PCB, please feel free to contribute. I welcome input from the DIY electronics community.

#### License
This Matrix Keyboard PCB project is provided under the MIT License. You are free to modify, distribute, and use it for personal and non-commercial purposes. Please refer to the full license documentation for more details.
