# 300 - Building Our Application

For support, visit [Help & Support](https://support.konnected.io) at Konnected.

WE ARE HERE ...

## 100 - Connecting via WiFi

See [Connecting to Your Network](https://support.konnected.io/connecting-to-your-network).


## 999 - Connect Konnected Alarm Panel Pro with Home Assistant

Based on "A minimalistic tutorial on Home Assistant - Konnected Alarm board integration" at https://github.com/scarpazza/home-assistant-konnected-tutorial

Based on "Add a Konnected Device to Home Assistant with ESPHome" at https://support.konnected.io/add-a-konnected-device-to-home-assistant-with-esphome

**New in 2023!** Konnected now provides pre-built ESPHome firmware for all Konnected products. We recommend that new Home Assistant users follow these steps to get started quickly with Konnected and Home Assistant powered by ESPHome.

**NOTE**: We have Konnected Alarm Panel Pro **version 1.8**.

Pre-requisites: 

1) Have your Konnected Alarm Panel Pro powered up with the supplied Power Supply (12 Volt DC).
2) Have an Ethernet cable connected between your Router (connected to the Internet) and your Konnected Alarm Panel Pro; a blue light will be pulsing.
3) Connect from your computer (Windows or Mac) via its USB port a mini USB cable to the Konnected Alam Panel Pro mini USB port. **TIP** Also have the Power Supply connected to provide enough power to the Konnected Alarm Panel Pro whilst flashing the firmware to support ESP Home.
4) Have setup WiFi connectivity previously as a backup scenario if Ethernet connectivity fails.

Browse for https://install.konnected.io/esphome

### ESPHome Runs on Konnected Hardware

Connect locally to Home Assistant and/or customize your Konnected Alarm Panel firmware with Konnected's ESPHome base firmware and open-source recipes. [Learn more on GitHub at konnected-io/konnected-esphome](https://github.com/konnected-io/konnected-esphome).

Choose a firmware build, plug in your board, and click Connect to quickly get started using ESPHome & Home Assistant with your Konnected Alarm Panel:

Choose ==> Ethernet (Alarm Panel Pro v1.8 and up)

Click **CONNECT**

You will be prompted as follows:

```
No port selected

If you didn't select a port because you didn't see your device listed, try the following steps:

1. Make sure that the device is connected to this computer (the one that runs the browser that shows this website)
2. Most devices have a tiny light when it is powered on. If yours has one, make sure it is on.
3. Make sure that the USB cable you use can be used for data and is not a power-only cable.
4. Make sure you have the right drivers installed. Below are the drivers for common chips used in ESP devices:
--- CP2102 drivers: [Windows & Mac](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)
--- CH342, CH343, CH9102 drivers: [Windows](https://www.wch.cn/downloads/CH343SER_ZIP.html), [Mac](https://www.wch.cn/downloads/CH34XSER_MAC_ZIP.html)
(download via blue button with  icon)
--- CH340, CH341 drivers: [Windows](https://www.wch.cn/downloads/CH341SER_ZIP.html), [Mac](https://www.wch.cn/downloads/CH341SER_MAC_ZIP.html)
(download via blue button with  icon)

CANCEL     TRY AGAIN
```

**TIP**: [How can I tell charge-only USB cables from USB data cables?](https://electronics.stackexchange.com/questions/140225/how-can-i-tell-charge-only-usb-cables-from-usb-data-cables)

Follow above instructions, then try again.

After a successful install on Mac of the CP2102 drivers, when trying again you will be shown a list of connected devices (in our case: ```cu.Bluetooth-Incoming-Port -- Paired```). Choose the one and you will be prompted again as:

```
Device Dashboard

Install Konnected Alarm Panel for ESPHome (RTL8201)

Logs & Console
```

Click on ```Install Konnected Alarm Panel for ESPHome (RTL8201)```

You will be asked to confirm as follows:

```
Confirm Installation

Do you want to install Konnected Alarm Panel for ESPHome (RTL8201) 0.3.2?

All data on the device will be erased.

Back     Install
```

Click on ```Install```

In case a failure occured you will see:

```
Installation failed

Failed to initialize. Try resetting your device or holding the BOOT button while clicking INSTALL.

BACK
```

We will hold down the BOOT button in the Konnected Alarm Panel Pro (labelled REBOOT) while clicking INSTALL again.


**TIP**: [Unable to manually update firmware (Konnected Alarm Pro)](https://community.konnected.io/t/unable-to-manually-update-firmware-konnected-alarm-pro/25480)

MORE ...


