# Users's Guide
## Online Mode (<font style="color:rgb(64, 64, 64);background-color:rgb(252, 252, 252);">Interactive Mode）</font>
### Usage Introduction
In Online Mode, the ICRobot can communicate with the PC via Serial Port, Bluetooth, AP, or STA, allowing you to program and control the robot to perform actions.

### <font style="color:rgb(64, 64, 64);background-color:rgb(252, 252, 252);">Steps</font>
| ![](IMG/U1.gif) | ![](IMG/U2.png) |
| :---: | :---: |
| Step 1. After both the ICRobot and the programming software are powered on, switch the software mode to Online Mode. Then select the<br/> device and the connection method. <br/>(For connection options and detailed steps, refer to [Serial Port Connection Mode](), [Bluetooth Connection Mode](https://icreaterobot-icrobot-docs.readthedocs.io/en/latest/docs/ICRobot/04OperationManual/01ConnectionMethod/03BluetoothModeBTMode.html),<br/> [Wireless Access Point (AP) Mode](https://icreaterobot-icrobot-docs.readthedocs.io/en/latest/docs/ICRobot/04OperationManual/01ConnectionMethod/01AccessPointModeAPMode.html), and [Client (STA) Mode](https://icreaterobot-icrobot-docs.readthedocs.io/en/latest/docs/ICRobot/04OperationManual/01ConnectionMethod/02StationModeSTA.html).) | Step 2. Once the selection is successful, the Block Commands panel will automatically load the ICRobot-related extension blocks. |
| ![](IMG/U3.png) |![](IMG/U4.png) |
| Step 3.  Drag the required blocks into the Coding Area to create your program. | Step 4. After programming is complete, click the green flag to execute the program and observe the result. |


### Example
#### Scenario
Using AP mode, ICRobot connects to the PC and moves forward at full power for 1 second, then activates its robotic gripper once.

#### Preparation
| ![](IMG/U5.png) | ![](IMG/U6.png) | ![](IMG/U7.png) |
| :---: | :---: | :---: |
| A computer (Windows/macOS) | ICreate Code | ICRobot |


#### Steps
| ![](IMG/U8.gif) | ![](IMG/U9.gif) |
| :---: | :---: |
| Step 1. Power on ICRobot and switch to AP mode via the SET menu. | Step 2. Open the programming software ICreate Code. Check the ICRobot’s Wi-Fi name (SSID) in your system WLAN/Wi-Fi list in advance, then select AP as the connection method in the software to connect. |
| ![](IMG/U10.png) | ![](IMG/U11.png) |
| Step 3. After the connection is successful, program the target content.   | Step 4. Click the green flag to run the program and observe the results. |


#### Demonstration
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/U12.gif)

## Download Mode
### Usage Introduction
The programming content can be downloaded to the ICRobot and executed on the robot. The download steps are as follows:

1. In the software, confirm the target download slot/location for the program.
2. Download the program to the built-in program storage of Robot Car 1–5.
3. Based on the program content, control the robot to execute the corresponding action commands.

### Steps
| ![](IMG/U13.gif) | ![](IMG/U14.png) |
| :---: | :---: |
| Step 1. After both the ICRobot and the programming software are powered on, switch the <br/>software mode to Interactive Mode. Then select the device and the connection method. <br/>(For connection options and detailed steps, refer to [Serial Port Connection Mode](), <br/>[Bluetooth Connection Mode](https://icreaterobot-icrobot-docs.readthedocs.io/en/latest/docs/ICRobot/04OperationManual/01ConnectionMethod/03BluetoothModeBTMode.html), [Wireless Access Point (AP) Mode](https://icreaterobot-icrobot-docs.readthedocs.io/en/latest/docs/ICRobot/04OperationManual/01ConnectionMethod/01AccessPointModeAPMode.html), and [Client (STA) Mode](https://icreaterobot-icrobot-docs.readthedocs.io/en/latest/docs/ICRobot/04OperationManual/01ConnectionMethod/02StationModeSTA.html).)   | Step 2. Once the selection is successful, the Block Commands panel will automatically load the ICRobot-related extension blocks. |
| ![](IMG/U15.gif) | ![](IMG/U16.gif) |
| Step 3. Drag the command blocks into the Coding Area to create the program. While dragging the blocks, <br/>the Python Coding Area will display the corresponding Python code for each block. | Step 4. After completing the programming, click the Download option in the Hardware <br/> Control Panel to download the programmed content to the ICRobot’s built-in program <br/> storage (with 5 available slots: 1–5). |


### Example
#### Scenario
The ICRobot connects to the PC via STA Mode, making the robot move forward at maximum power for 1 second. After that, the display shows the custom dot matrix effect. The program content is downloaded to the built-in program storage at position 3.

#### Preparation
| ![](IMG/U17.png) | ![](IMG/U18.png) | ![](IMG/U19.png) |
| :---: | :---: | :---: |
| A computer (Windows/macOS) | ICreate Code | ICRobot |


#### <font style="color:rgb(64, 64, 64);background-color:rgb(252, 252, 252);">Steps</font>
| ![](IMG/U20.gif) | ![](IMG/U21.gif) |
| :---: | :---: |
| <font style="color:rgb(64, 64, 64);background-color:rgb(252, 252, 252);">Step 1. Power on ICRobot. Switch to SET Mode, then select STA Mode.</font> | Step 2. Open the programming software ICreate Code, and select the STA connection method in the software to establish the connection.<br/> A corresponding QR code will be generated. |
| ![](IMG/U22.png) | ![](IMG/U23.gif) |
| Step 3. Point the ICRobot camera at the QR code on the screen to scan and connect. Once connected, a message will appear saying "Connection Successful" <br/>and the page will display "Socket Connection Successful", indicating the device has successfully connected. | Step 4. After a successful connection, proceed to program the target content. |
| ![](IMG/U24.gif) | ![](IMG/U25.gif) |
| Step 5. After selecting position 3, click Download. Once the download is complete, a message will appear saying "Download Successful". | Step 6. After selecting position 3, click Download. Once the download is complete, a message will appear saying "Download Successful". |


#### Effect display
<!-- 这是一张图片，ocr 内容为： -->
![](IMG/U26.gif)

