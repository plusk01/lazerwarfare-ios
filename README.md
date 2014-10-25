Lazer Warfare iOS
================

This is the iOS version of the LazerWarfare Android app.

The app was originally written by Adam Burnett, BYU student, for his senior project ([source code](https://github.com/ihavenoface5/LazerWarfare)). The project that his team built was the software interface for the EE Junior Core project, which is to build a working set of lasertag guns.

The guns work by modultaing LEDs at different frequencies. Each gun has its on frequency, allowing other players to identify who hit them. Each gun is controlled by the Xilinx Zybo board, which communicates with the app through Bluetooth LE. The app then talks to a server through a RESTful API written in Python/Django by Zack Argyle ([source code](https://github.com/zackargyle/senior-project)).


-----------------------------------------------------------------------

## Reference Material ##

+ [Software Team API Documentation](http://lasertag.groups.et.byu.net/doku.php?id=server_group_page)
+ The released Android app in the [Google Play Store](https://play.google.com/store/apps/details?id=com.laserwarfare&hl=en)
