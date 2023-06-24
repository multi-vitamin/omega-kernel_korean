#EZ-FLASH OMEGA Kernel

--------------------------------------
### Korean font

Galmuri11 (https://galmuri.quiple.dev)

### Differences from Original Kernel
1. Chinese changed to Korean
2. Corrected a broken first word error when Filename_loop function with long Korean file name
--------------------------------------
### How to install

1. Download ezkernel.bin from release
2. Move ezkernel.bin file to root of sd card
3. Press and hold R button while booting Omega DE
4. When update screen appears, release R button and be careful not to turn off the power until completion
5. After update is completed, change language from Settings to Korean
--------------------------------------

### How to build 

    1.you can use latest version of devkitARM.
    2.Set the following environment variables in system, or modify the value in build.bat, based on your installation path
 
        PATH,DEVKITARM,DEVKITPRO,LIBGBA

    3.Double click on build.bat under winodws. If it goes well, you will get ezkernel.gba
    4.Rename the ezkernel.gba to ezkernel.bin, that is the omega kernel upgrade file
