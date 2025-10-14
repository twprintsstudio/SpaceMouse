# SparkFun Arduino Pro Micro Board (5v,16MHz) with updated values for compatibility with 3dconnections software

This repository contains support for the following SparkFun Arduino-compatible development boards that have been modified to be recognized by the 3dconnections software.

**IMPORTANT NOTE:** These board files have been updated for compatibility with Arduino version 1.8 and higher. Some boards may not compile correctly with earlier versions of Arduino. If you need compatibility with earlier versions of Arduino, you can choose previous releases of these boards from the Boards Manager.


- [Pro Micro 5V (with updated vidx0 and pidx0 values)](https://www.sparkfun.com/products/11098)


### Installation Instructions

To add board support for our products, start Arduino and open the Preferences window (**File** > **Preferences**). Now copy and paste the following URL into the 'Additional Boards Manager URLs' input field:

    https://raw.githubusercontent.com/twprintsstudio/SpaceMouse/main/IDE_Board_Manager/package_thomas_spacemouse_index.json


![Adding Link Step 1](AddLink.png)
![Adding Link Step 2](AddLinkPt2.png)
![Adding Link Step 3](AddLinkPt3.png)
![Adding Link Step 4](ExitLink.png)

![Adding The Board Step 1](BoardsManagerPt1.png)
1[Adding The Board Step 2](BoardManager.png)

If you type "spacemouse" (without quotes) into the "filter your search" field, you will see options to install SpaceMouse AVR Boards files. Click in the desired box, and click the "Install" button that appears. Once installed, the boards will appear at the bottom of the board list.

![Selecting Board](BoardSelection.png)
