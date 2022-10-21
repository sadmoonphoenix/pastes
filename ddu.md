DDU is a tool to uninstall graphics drivers. This is useful for resetting the drivers to stock, or to swap out the driver version. 

1. Download DDU. (https://www.guru3d.com/files-details/display-driver-uninstaller-download.html)
2. Download the proper drivers. NVIDIA: https://www.nvidia.com/Download/index.aspx?lang=en-us; AMD: https://www.amd.com/en/support; Intel: https://www.intel.com/content/www/us/en/download-center/home.html
3. Go to Control Panel. (Windows Key + R, type `control`, press enter)
4. Change "View by" (top right) to "Large Icons". Select "Network and Sharing Center".
5. On the left side of the screen, select "Change adapter settings."
6. Right click each adapter, and press "Disable" if not already. Take a note of each one you disable, you'll want to enable these later.
7. Boot into safe mode. (https://support.microsoft.com/en-us/windows/start-your-pc-in-safe-mode-in-windows-92c27cff-db89-8644-1ce4-b3e5e56fe234) NOTE: Select "Safe Mode" and NOT "Safe Mode with Networking"
i. You might get a prompt warning you you're not connected to the Internet. Ignore it.
8. Open the DDU file. It will prompt you to extract to a location. Choose a local location (physical storage [like C or D disk], not cloud storage [like Google Drive]). Open the folder that extracts, and open the application inside.
9. Under "Select Device Type" choose "GPU". Then under "Select Device" select AMD, NVIDIA, or Intel. 
10a. If you have only one graphics card/more than one from the same company (i.e. AMD), select "Clean and restart." 
10b. If you have two from different companies (i.e AMD and NVIDIA), select "Clean and DO NOT restart" for the first one. Then select the other GPU and select "Clean and restart"
10c. If you are using DDU to *swap* your GPU, select "Clean and shutdown". Then replace your GPU (be safe!)
11. Go to where you saved your display driver from earlier. Open it and install it. If you're running Windows 8 or later, it might warn you that it cannot reach SmartScreen and cannot check if the file is safe. This is because you don't have Internet, and you SHOULD NOT have the internet. Press Run.
i. You may have to press "More Info" to see the Run Anyway/Run button.
12. Enable the network adapters you had disabled and reconnect to the Internet.
