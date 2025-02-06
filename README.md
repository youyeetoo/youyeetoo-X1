# X1

![image](https://wiki.youyeetoo.com/x1/image/3.jpg)

中文wiki看这里：
https://wiki.youyeetoo.cn/zh/x1
> The youyeetoo X1 is an x86-based single board computer (SBC) launched by youyeetoo.com. It supports full-featured versions of Windows and Linux, which is designed for the AIOT and automation market. With its compact size (115mm * 75mm) and high performance (11th Gen Intel CPU N5105), it offers a range of interfaces commonly used in AIOT applications, including 3x UART, 2x HDMI, 2x USB 3.0, 4x USB 2.0, 1x I2C, 1xSPI, and 5x GPIO. It also supports a 7-inch MIPI touch screen. The recommended model (8GB DDR + 128GB eMMC) is competitively priced at $129, making it an ideal choice for AI edge computing.

# Certification certificate
 - [Certificate | *CE Test Report* | *CE Certificate* | *FCC Test Declaration* | *FCC Certificate* | *RoHS Test Report* | *RoHS Certificate*](https://drive.google.com/drive/folders/12ySbJGgRy3uERCIPjt4aVUCihVm5nhlg?usp=sharing)

# SPECIFICATIONS
| Item   |      descriptions      |
|:----------:|:-------------|
| **CPU:** |  Intel® Celeron 11'th Gen Jasper Lake N5105 (CPU Frequency: 2.0~2.9GHz，Quad-core 10nm TDP 10W) |
| **GPU:**|  Intel®UHD Core Graphics(Frequency:450 - 800MHz)   |
| **Memory:**| Onboard 4GB / 8GB /16GB  LPDDR4  (<span style="color:#ff0000">optional</span>)    recommend 8GB  |
| **Storage:** |**eMMC**(V5.1): 0/64G/128G/256G  (<span style="color:#ff0000">optional</span>)   <br /> **M.2 Slots** ：NVMe 2280 SSD(PCIE3.0)  or M.2 SATA 2280 SSD  <br />  (Support PCle Gen 3.0 x4 lanes NVMe 1.4，compatible with PCle Gen 3.0 x2 NVME) <br /> **SATA FPC Slots**：SATA3 hard disk can be expanded through SATA adapter board（<span style="color:#ff0000">need SATA adapter board</span>）  <br /> **Micro SD(TF)** : Supports common SD cards  to Extended storage|
|**network:**| **Ethernet:** RJ45 Gigabit Ethernet * 1 <br /> **Wireless:** WIFI5+BT5.0 / WIFI6+BT5.2 Expansion via M.2 slot, (<span style="color:#ff0000">optional</span>) <br /> **4G LTE:** M.2 E-key slot expansion,4G datamodule such as the EC20/EC25(**need 4G adapter board**) |
|  **Display**  <br />（Multi screen)| **HDMI**:HDMI2.0 4K/60Hz <br /> **Micro HDMI**：HDMI2.0 4K/60Hz   <br />  **MIPI FPC** ：Support Youyeetoo MIPI7LCD(1024 * 600 ) LCD module  Multi TOUCH |
|  **USB**| USB-A: USB2.0 * 2 (Limit 1.45A total) Two interfaces share 1.45A<br /> USB-A: USB3.0 * 2 (Limit 1.45A  total)Two interfaces share 1.45A<br /> USB Pin: USB2.0 * 2 (Limit 1.45A  total)Two interfaces share 1.45A|
| **Audio Output** | 3.5 Headphone jack(4line),headset with MIC <br /> SPK XH2.0 PIN: Onboard 3W power amplifier,matching 8 ohm speakers <br /> HDMI Audio Output (Audio can be output to TV via HDMI) |
| **Audio Input** |1. Onboard digital microphone MIC:with noise reduction function(default) <br />2. Analong MIC: SH0.8mm 2PIN head on the back, 3.3V analog microphone (Switch MIC lnput needs to replace BlOS) |
| **M.2 Socket** |  M.2 M Key: NVME SSD/M.2 SATA SSD <span style="color:#ff0000">(M-key) 2280 </span>  <br /> M.2 E Key: WIF15+BT5.0/WIFI6+BT5.2 Module 2230 or 4G adapter board to support 4G LTE module <span style="color:#ff0000">(E-key)</span> |
| **UART** |UART TTL * 3 serial port, XH2.0, 4PIN, Connect RS232 or RS485 /CAN modules can also be use |
| **I2C** | IIC * 1 XH2.0 4PIN，Provide windows/linux operation example tutorial Default 3.3V |
| **SPI** | SPI* 1 XH2.0 5PIN，Provide windows/linux operation example tutorial Default 3.3V |
| **GPIO** | GPIO * 5 XH2.0 6PIN，Provide windows/linux operation example tutorial Default 3.3V |
| **LED light** | Onboard LED * 2，Parallel 4PIN pin lead, XH2.0, Default 3.3V (defaultred flashes and green off)(Provide a tutorial API interface to control heartbeat flickering) |
| **key** | Power key * 1 Reset key * 1(restore BIOS setting) |
| **RTC** | RTC battery Seat : SH1.25 2PIN CR2032 button battery or other 3.3V battery <br /> RTC consumes about 35mAh per year |
| **Auto Power-on** |  Turn on * 1 without pressing the power button(can be set in BIOS) |
| **Power** | 12V DC socket(5.5*2.5): Recommended power adapter 12V3A or XH2.54 2PIN Power socket |
| **Dimension** | 115 * 75 mm |
| **Heat sink** | FAN seat specification:SH1.0 4PIN Default heatsink fan 5V/0.2A power Consumption |
| **Multi OS** | Windows 10/11Linux ubuntu / Linux Debian |
| **NFC** | NFC device.data transmission with mobile phones/Card Reader, Compatible with android/lOS phones,youyeetoo wiki provides examples |
| **Intel watchdog** | Implemented via standard windows API |
| **CPU temperature reading** | Implemented via standard windows API |
| **CPU Fan Speed Adjustment** | Implemented via standard windows API Fan speed requlation |
| **POE**  |default Support AC/BT protocol 30W POE module,<span style="color:#ff0000">(Need buy POE module additional)</span> <br />60W support (need to change the power chip on board) contact us |

# Interface 
**V3**：
![7a1d22c870f67eebbd707c72fedb978.jpg](https://wiki.youyeetoo.com/x1/image/7a1d22c870f67eebbd707c72fedb978.jpg)
![接口图__背面.jpg](https://wiki.youyeetoo.com/x1/image/%E6%8E%A5%E5%8F%A3%E5%9B%BE__%E8%83%8C%E9%9D%A2.jpg)
**V2**:
![接口图_正面.jpg](https://wiki.youyeetoo.com/x1/image/%E6%8E%A5%E5%8F%A3%E5%9B%BE_%E6%AD%A3%E9%9D%A2.jpg)
![接口图_背面.jpg](https://wiki.youyeetoo.com/x1/image/%E6%8E%A5%E5%8F%A3%E5%9B%BE_%E8%83%8C%E9%9D%A2.jpg)

- [More detailed hardware description | *2D image* | *schematic diagram*](http://wiki.youyeetoo.com/en/x1/IntroductiontoDevelopmentBoard)



# Getting Started Tutorial
## Power on and start up
- [Getting started tutorial | *Preparation for startup* | *About power supply* | *Change the power-on auto-start or power-on button* | *Housing installation*](https://wiki.youyeetoo.com/en/x1/windows/Hardware-preparation)


# Accessory
- [Display screen | *10.1HDMI screen* | *7-inch mipi screen*](https://wiki.youyeetoo.com/en/x1/parts/screen)
- [Camera | *usb camera* ](https://wiki.youyeetoo.com/en/x1/parts/Camera)
- [YYT-UART | *UART expansion board* ](https://wiki.youyeetoo.com/en/x1/parts/YYT-UART)
- [NFC | *NFC antenna* ](https://wiki.youyeetoo.com/en/x1/windows/nfc_driver)
- [4G | *EC20 4G module* ](https://wiki.youyeetoo.com/en/x1/parts/4G)
- [WIFI/BT | *RTL8852BE module* | *RTL8822CE module* ](https://wiki.youyeetoo.com/en/x1/parts/WIFI-BT)
- [POE | *POE module* ](https://wiki.youyeetoo.com/en/x1/FAQ/PoE)
- [SATA adapter board | *FPC to SATA adapter board* ](https://wiki.youyeetoo.com/en/x1/parts/SATA)
- [Battery | *RTC battery* ](https://wiki.youyeetoo.com/en/x1/parts/Battery)
- [USBI2C | *USBI2C instructions* ](https://wiki.youyeetoo.com/en/USBI2C)

# Windows
## Installation system
- [Install the Windows system | *Download Windows from the official website and install it on the board*](https://wiki.youyeetoo.com/en/x1/windows/install-system)
## Update BIOS
- [Getting Started Tutorial | *Update BIOS* ](https://wiki.youyeetoo.com/en/x1/FAQ/enter_bios)
## Install the driver
- [Install driver | *Install driver for Ubuntu system on board*](https://wiki.youyeetoo.com/en/x1/windows/install-driver)
## MIPI7LCD display
- [MIPI7LCD monitor | *using mipi 7-inch screen*](https://wiki.youyeetoo.com/en/x1/windows/MIPI7LCD)
## WIFI/Bluetooth
- [WIFI/Bluetooth | *using WiFi and Bluetooth functions*](https://wiki.youyeetoo.com/en/x1/windows/wifi-bt)
## Camera
- [Camera | *Using a camera*](https://wiki.youyeetoo.com/en/x1/windows/camera)
## 4G LTE
- [4G LTE | *using 4G modules*](https://wiki.youyeetoo.com/en/x1/windows/4G-LTE)

# Windows Driver Development
## Introduction to windows desktop driver development 
Basic Knowledge Preparation: Familiar with C/C++ programming language and understand the concepts of function pointers, callback functions and event handlers. basic use of Visual Studio.

## Drivers are categorized into the following types
1. device function drivers
2. device filter drivers
3. software drivers
4. file system filter drivers
5. file system drivers

## **Software Driver Development Classification**
Categorized into the WDM model and the WDF model, WDM drivers are trusted kernel-mode components, so the system provides limited checks on driver input. In contrast, the WDF model focuses on the requirements of the driver, and the framework library handles most of the interaction with the system. Microsoft recommends using the WDF model for new driver development.
The WDF model is divided into two types of driver development: KMDF kernel mode drivers and UMDF user mode drivers. We often say that the development is the KMDF kernel mode driver.

## **Development environment:**
VS2022 + SDK (according to the target board system version to download) + driver toolkit WDK
VS2022 installation: select "desktop development using c++" and "Visual Studio extension development" two contents.
The SDK can be installed on the network, and the WDK can be installed on the network.
For installation, please refer to the Microsoft tutorial: https://learn.microsoft.com/zh-cn/windows-hardware/drivers/download-the-wdk#download-and-install-the-windows-11-version-22h2-wdk

## **Introduction to the process of creating a KMDF driver:**
Start Visual Studio.
In the startup dialog box, select "Create New Project", or select "Project" in the "New | Visual Studio File" menu. Select "Create New Project" in the startup dialog box or select "Project" from the "New | Visual Studio" File menu.
In the right pane of the Create New Project dialog box, locate and select Kernel Mode Driver (KMDF). Select Next.
Fill in the Project Name, Location and Solution Name boxes and select Create. For more information, see Writing KMDF Drivers Based on Templates.
At this point, your driver project implements the general code required by most KMDF drivers. You can now provide code specific to your device.

## **Driver installation and debugging**
During the debugging phase, the target machine needs to be configured in test mode, otherwise the driver cannot be installed.
Run the following terminal command with administrator privileges: bcdedit /set testsigning on to reboot the system.
If you don't want to test anymore, exit the test mode: bcdedit /set testsigning off and reboot the system.

Compile the driver folder, copy it to the target machine, there is a file "XXX.inf" in the driver folder on the target machine, right click the mouse to install it.
Because the driver debugging and common application debugging methods are different, generally by viewing the driver process log to determine and analyze whether the driver is running normally.
Need to use Microsoft's tools.
DebugView (view ktprint print log) Download: https://learn.microsoft.com/zh-cn/sysinternals/downloads/debugview
Driver Monito (view the log of the WPP framework) download address: https://www.drivers.com/download-monitor-drivers/

## **Driver Signature**
When the driver debugging good, no problem, need to give the driver signature, the driver can be installed in the official mode of the system.
Driver signing: you can let Microsoft sign the driver, or let a third-party organization to help sign the driver. The price is different.
 

## **New device added to the system:**
To mount an external device via I2C/SPI bus, you need to declare the device in the ASL CODE of the motherboard, so that the new device will appear in the device manager of the system.
How to add a new device will be mentioned later in the I2C/SPI/NFC development.
The target system in test mode, driver development process, do not brush the BIOS, the new device can be injected into the registry, you can carry out development and testing.
The process of injecting a new device into the registry (this process is only effective when the system is in test mode).
Tools used: 1.
1.SDK comes with asl.exe: path C:\Program Files (x86)\Windows Kits\10\Tools\SDK specific version number\x64\ACPIVerify\

2.iasl-win: download address:https://www.intel.com/content/www/us/en/download/774881/acpi-component-architecture-downloads-windows-binary-tools.html

In the target machine as administrator, run the following commands.

**1) Read the BIOS configuration from the registry cache and save it to the DSDT0000.bin file**.
```key
 .\asl.exe /tab=DSDT /c
```
**2) Decompile DSDT0000.bin file, generate DSDT0000.dsl (ASL CODE file)**.
```key
.\iasl.exe -ve . \DSDT0000.bin
```
**3) Modify the DSDT0000.dsl file, add new devices to change the file**

According to the actual need to add devices to the file, followed by the use of I2C/SPI/NFC in the introduction of specific examples need to add the content.

**4) Compile the modified DSDT0000.dsl, which will generate DSDT0000.aml file**
```key
.\iasl.exe -ve . \DSDT0000.dsl
```
**5) Write to registry cache**
```key.
.\asl.exe /loadtable DSDT0000.aml
```
**6)Ignore signature**
```key
Bcdedit /set testsigning on
```
**7)Reboot the system so that you can see the new device in the device manager.**

To disable the ASL code, uninstall it.
```key
key. \asl.exe /loadtable DSDT0000.aml -d 
```
Reboot the system, and you will be back to the unadded device state.

When the new device is ready for debugging, you need to update the BISO code and re-flash the BIOS.
# Windows Application Development
This tutorial is an example of how to call the hardware resources on the youyeetoo X1 motherboard in a windows application, to make it easier to control the hardware in real projects.
## GPIO Usage
- [GPIO Development | *Operate GPIO input and output*](https://wiki.youyeetoo.com/en/x1/windows/gpio_driver)
## I2C usage
- [I2c interface development | *Operate I2C read and write*](https://wiki.youyeetoo.com/en/x1/windows/i2c_driver)
## SPI usage
- [SPI interface development | *SPI interface test*](https://wiki.youyeetoo.com/en/x1/windows/spi_driver)
## NFC usage
- [NFC development | *Onboard NFC development test*](https://wiki.youyeetoo.com/en/x1/windows/nfc_driver)
## LED Light Control
- [LED Control | *Onboard LED Control Test*](https://wiki.youyeetoo.com/en/x1/windows/led_driver)
## SPK/Headphone/HDMI Audio Output Switching
- [SPK/Headphone/HDMI Audio Output Switching | *Audio Output Switching*](https://wiki.youyeetoo.com/en/x1/windows/switch_voice)
## MIC input toggle - BIOS change required
- [MIC input toggle | *Need to change BIOS*](https://wiki.youyeetoo.com/en/x1/windows/switch_mic_input)
## Watchdog usage
- [Watchdog | *Watchdog on and off*](https://wiki.youyeetoo.com/en/x1/windows/wdog)
## Obtain a unique ID identification code
- [Obtain a unique ID identification code | *Get X1 UID*](https://wiki.youyeetoo.com/en/x1/windows/getuid)
# Linux
## Installation system
- [Install the Ubuntu system | *Download Ubuntu from the official website and install it on the board*](http://wiki.youyeetoo.com/en/x1/linux/install-system)
## MIPI7LCD display
- [MIPI7LCD monitor | *using mipi 7-inch screen*](http://wiki.youyeetoo.com/en/x1/linux/MIPI7LCD)
## WIFI/Bluetooth
- [WIFI/Bluetooth | *using WiFi and Bluetooth functions*](http://wiki.youyeetoo.com/en/x1/linux/wifi-bt)
## Camera
- [Camera | *Using a camera*](http://wiki.youyeetoo.com/en/x1/linux/camera)
## 4G LTE
- [4G LTE | *using 4G modules*](http://wiki.youyeetoo.com/en/x1/linux/4G-LTE)
# Linux application development (calling hardware)
1. This tutorial takes ubuntu-22.04.x-desktop-amd64 as an example, and the basic tools used in application development are installed as follows:
```
#update soft list
sudo apt-get update

# install make
sudo apt install make
sudo apt -y install make-guile

#install gcc g++
sudo apt  -y install gcc
sudo apt  -y install g++

# install cmake
sudo snap install cmake
sudo apt  -y  install cmake 

#install git
sudo apt -y  install git build-essential dkms  --force-yes

#install vim
sudo apt -y install vim

#install curl
sudo apt -y install curl

#install wget
sudo apt -y install wget
```
2. Linux application development, knowledge reserve: Fundamentals of C/C++programming development, foundation of make compilation and Makefile writing

## GPIO usage
- [GPIO Development(Linux) | *Operate the input and output of GPIO*](https://wiki.youyeetoo.com/en/x1/linux/gpio_driver)
## I2C usage
- [I2c interface development(Linux)  | *Operation I2C read and write*](https://wiki.youyeetoo.com/en/x1/linux/i2c_driver)
## SPI usage
- [SPI interface development(Linux) | *SPI interface testing*](https://wiki.youyeetoo.com/en/x1/linux/spi_driver)


## NFC usage
- [NFC Development(Linux) | *Onboard NFC development and testing*](https://wiki.youyeetoo.com/en/x1/linux/nfc_driver)
## LED light control
- [LED light control(Linux) | *Onboard LED control test*](https://wiki.youyeetoo.com/en/x1/linux/led_driver)
## SPK/headphone/HDMI audio output switching
- [SPK/headphone/HDMI audio output switching(Linux) | *Audio output switching*](https://wiki.youyeetoo.com/en/x1/linux/switch_voice)


## MIC input switching - BIOS needs to be changed
- [MIC input switching(Linux) | *BIOS needs to be changed*](https://wiki.youyeetoo.com/en/x1/linux/switch_mic_input)


## Wired network fixed IP/DHCP automatic acquisition of IP
- [IP settings for wired networks(Linux) | *Set static IP or automatically obtain IP*](https://wiki.youyeetoo.com/en/x1/linux/wired_network_ip)
## UART serial port usage
- [UART serial port development(Linux) | *UART serial port test*](https://wiki.youyeetoo.com/en/x1/linux/uart_driver)
## Watchdog usage
- [Watchdog(Linux) | *Watchdog on and off*](https://wiki.youyeetoo.com/en/x1/linux/wdog)
## Obtain a unique ID identification code
- [Obtain a unique ID identification code(Linux) | *Get X1 UID*](https://wiki.youyeetoo.com/en/x1/linux/getuid)


# FAQ
## Accessory Installation
- [Install hard drive | *NVMe SSD* | *SATA SSD* | *adapter board connected to SATA3 hard drive*](https://wiki.youyeetoo.com/en/x1/FAQ/hard_drive)
- [Install WIFI/BT module | *WIFI5* | *WIFI6* ](https://wiki.youyeetoo.com/en/x1/windows/wifi-bt)
- [POE | *POE module* ](https://wiki.youyeetoo.com/en/x1/FAQ/PoE)
## BIOS
- [How to enter BIOS | *BIOS Setting* | *Wake on Lan*](https://wiki.youyeetoo.com/en/x1/FAQ/enterbiosmode)
- [Update BIOS](https://wiki.youyeetoo.com/en/x1/FAQ/enter_bios)
## How to install windows driver
- [How to install youyeetoo X1 windows driver.](https://wiki.youyeetoo.com/en/x1/FAQ/install-win-driver)
