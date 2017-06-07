#RemoteAccessor

This enables person sitting on a server computer to execute any command on a client computer provided the following conditions:

    1. Both client as well as server computer are connected to the same LAN network.
    2. Client knows the IP address of server computer which is connected to the same LAN.

#System Requirements:

    1. Windows OS (At least on Client computer)
    2. A working LAN connecting two computers.

#Steps to setup this on your system:

    1. Download Server.java on server computer and compile using jdk 1.7 or above.
    2. Download Client.java on client computer and compile using jdk 1.7 or above.
    3. Execute Server.class and then Client.class. Click on "Start Server" button on server window.
    4. Enter the IP address in the client window and click on connect. "Connected" should reflect on both client and server         windows.
    5. Enter any command you wish on server window.
    6. Click on execute button on client window to execute that command
