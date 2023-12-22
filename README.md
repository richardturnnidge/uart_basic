A simple example in BBC Basic to:

open UART port

send/receive UART data

close UART port

Run the basic program.
Typing keys will send that ascii out the serial uart.
Hit SPACE to chage to receive data mode.
Hit S to go to send data mode

Hit ENTER to exit

I am aware that this code is in no way optimised. It is just a working prototype.

In this example, I use the UART of Agon attached to a serial USB device plugged into my computer

Agon        PC

Tx    <->   Rx

Rx    <->   Tx

Gnd   <->   Gnd

