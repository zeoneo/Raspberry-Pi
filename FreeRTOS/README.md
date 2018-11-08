# FreeRTOS (Pi1,2,3 32Bit .. COMING SOON Pi3 AARCH64)
![](https://github.com/LdB-ECM/Docs_and_Images/blob/master/Images/FreeRTOS.jpg?raw=true)

I have been messing around with Task Switchers (Single/Multicore) in 32Bit or 64Bit mode and have decided to put some up. This is the easiest one to understand and start with being a simple redux of FreeRTOS. Yes it all boots from the standard SmartStart system as usually so it autodetect models etc.  So on this example we have the RTOS simply running on one core doing the boring time slicing. In the next example we will have two independent Task Switchers on Two different cores. Finally I am going to play around with multiple cores on one switcher.
>
Sorry it's a pretty boring example just moving a couple bars backwards forward, I will try and make some more advanced samples.
>
### > As usual you can copy prebuilt files in "DiskImg" directory 
###   Place onto a formatted SD card and put in PI to test <

To compile edit the makefile so the compiler path matches your compiler:
>
For Pi1: 
>     Make Pi1
For Pi2:
>     Make Pi2
For Pi3 in 32 Bit:
>     Make Pi3
     
To clean for full compile:     
>     Make Clean
     


