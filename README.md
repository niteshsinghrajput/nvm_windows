# nvm_windows

## Steps to setup NVM and Node in windows operating system

To install Node.js using NVM (Node Version Manager) on Windows, follow these steps:

1. <b>Download NVM:</b> Visit the NVM repository on GitHub (https://github.com/coreybutler/nvm-windows) and download the latest stable release of NVM for Windows.

2. <b>Install NVM:</b> Run the downloaded NVM installer. Follow the on-screen instructions to complete the installation. Choose the desired installation directory (e.g., C:\nvm) when prompted.

3. <b>Open Command Prompt:</b> Open the Command Prompt by pressing Win + R and then typing cmd in the "Run" dialog. Hit Enter to open the Command Prompt window.

4. <b>Verify NVM Installation:</b> In the Command Prompt, run the following command to verify that NVM is installed correctly:

    ```bash
    nvm --version
    ```

5. <b>Install Node.js:</b> To install a specific version of Node.js using NVM, run the following command:
    ```bash
    nvm install <version>
    ```
   Replace <version> with the desired Node.js version (e.g., 14.17.0).

6. <b>Set Node.js Version:</b> After installation, set the installed Node.js version as the active version by running the command:
   ```bash
   nvm use <version>
   ```
   Replace <version> with the Node.js version you installed.

7. <b>Verify Node.js Installation:</b> To verify that Node.js is installed correctly, run the following command in the Command Prompt:
   ```bash
   node --version
   ```
   It should display the version number of the installed Node.js.
  