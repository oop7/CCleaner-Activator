# **CCleaner Activation Script**

This script simplifies the process of activating CCleaner by automating the activation process with a single click. It includes features for copying necessary files and handling administrative privileges.

## 💪 Features

- Base64 Decoding: Decodes Base64-encoded files required for activation.
- Administrative Privileges: Requests elevation to run the script with administrative privileges.
- File Operations: Copies necessary files to the CCleaner installation directory.
- Interactive: Provides a simple menu for user interaction and options.

## 🛠️ Installation

### **Method 1**
1. Download: Obtain the latest version of the tool from the [releases page](https://github.com/oop7/CCleaner-Activator/releases).
2. Extract: Unzip the downloaded file to a directory of your choice.

### **Method 2**
1. **Open PowerShell as Administrator**:
   - Right-click the Start menu and select **Windows PowerShell (Admin)** or **Windows Terminal (Admin)**.
   - If prompted by User Account Control (UAC), click **Yes** to allow PowerShell to run with administrative privileges.

2. Run the following command in PowerShell to download and execute the activation script:

   ```powershell
   irm https://github.com/oop7/CCleaner-Activator/releases/download/v1.1/v1.1.zip -OutFile v1.1.zip; Expand-Archive v1.1.zip -DestinationPath . -Force; cmd.exe /c .\v1.1\script.bat
   ```

## 💻 Usage

### 1. Run the Script:
- Right-click on `script.bat` and select Run as Administrator to ensure proper permissions for file operations.
- If prompted for administrative privileges, click Yes to allow the script to run with the necessary permissions.

### 2. Follow the On-Screen Instructions:
- Choose an option from the menu:
- `1` to activate CCleaner.
- `2` to activate Hosts blocker.
- `3` to exit.
- If you select 1, the script will decode the Base64 encoded files, copy them to the appropriate directory, and provide feedback on the operation status.
- If you select 2, the script will activate Hosts blocker to avoid issues (optional).
- If you select 3, the script will exit.
## ✅ Troubleshooting

- **Administrative Privileges**: If the script does not prompt for administrative rights, ensure you are running it with the required permissions by right-clicking and selecting Run as Administrator.
- **File Paths**: Verify that the encoded.txt , encoded_2.txt , encoded_3.txt and ASCII_art.txt files are correctly placed in the src directory.
- **Warning**: The default installation path for the software is:
``C:\Program Files\CCleaner``
If the software is not installed in this directory, please ensure the path is correct before continuing.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ℹ️ Acknowledgments

- Special thanks to elchupacabra, which was instrumental in this script's functionality.

## ❓ Contact

For questions or support, please open an issue on the GitHub repository.

