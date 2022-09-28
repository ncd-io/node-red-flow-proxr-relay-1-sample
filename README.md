# node-red-flow-proxr-relay-1-sample
In this example we will use inject nodes to turn relay 1 on a ProXR controller on and off through a Digi Mesh wireless connection.

Note you will need to double click the Wireless Gateway Node and select the serial port for your USB modem.

You will need to open the two function nodes and locate the msg.payload.address variable and change to the serial address of your ProXR relay controller Digi Mesh module.  This address can be found on the bottom of the Digi Mesh wireless module installed in the board.

![The Flow is very Simple](https://github.com/ncd-io/node-red-flow-proxr-relay-1-sample/Screen Shot 2022-09-28 at 10.04.25 AM.png)
