# Zed Board Root File System
### Steps to write sdcard image to sdcard 
* Get a SD Card 8 GB or larger 
* Insert the SD Card into SD Card reader 
* run dmesg | grep sd
* once you identity the node run the following command 

    ```
        sudo dd if=zedboard-vave-sdcard.img of=/dev/diskn bs=1M
    ```
* Insert the SD Card image to ZedBoard SD card slot 
* Enjoy 
* File a bug report if you have any problem 



