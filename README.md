
# Cool-MOTD

Cool-MOTD (Message of the Day) is a customized message displayed when you log into your server, providing system information and weather updates.

## Dependencies

To run Cool-MOTD, you need to install the following dependencies:

- **cowsay**: Display ASCII art of a cow with customizable messages.
  ```bash
  sudo apt install cowsay

- **screenfetch**: Display system information including OS, kernel, CPU, memory and more.
    ```bash
  sudo apt install screenfetch
- **inxi**: A full-featured system information script.
    ```bash
    sudo apt install inxi

- **ansiweather**: Display current weather conditions and forecasts.

    ```bash
    sudo apt install ansiweather


## Usage:

To customize your Message of the Day (motd) on Debian/Linux, follow these steps:

1. **Access the motd directory:**
   On Debian, motd scripts are typically located in the directory `/etc/update-motd.d/`.

2. **Modify or create a new motd script:**
   - Use your preferred text editor to create or modify a motd script.
   - For example, create a file named `99-custom-motd` for your custom message. Ensure the filename starts with a number (`99-`) to determine the execution order of motd scripts.

   ```bash
   sudo nano /etc/update-motd.d/99-custom-motd

## Used By

This project is used by the following companies:

- Me 
- Microsoft
- Apple Company
- also you now 

## Screenshots

![App Screenshot](/images/99-custom.png)