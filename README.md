##  The Future of 3D printer Bed Leveling

[BDsensor](https://www.pandapi3d.com/bdsensor) is the first distance sensor that can work with 3D printer and do fast bed leveling and adjust z axis in real time.
it can measure the bed distance at any point in real time without moving the z axis up and down.

 <img src="https://raw.githubusercontent.com/markniu/Bed_Distance_sensor/new/doc/images/Connection1.jpg" width="600" /> 

Faster leveling, realtime compensation, high accuracy.

1. No need to do probe points before every print, it will be automatically compensated for based on actual distance in real time.
 
2. You can do bed mesh leveling like a normal proximity sensor but much faster with this BDsensor.
   
3. Thanks for the distance value can be shown on the screen, you can do manual bed leveling more easily.

Sensor type: inductive, can only measure the metal plate.

Range: 4mm

Resolution:0.01mm

### Hardware:
* Support all the mainboards
* Easy to install:

  small and light; can be installed anywhere, even surrounding metal above;no need to open the mainboard box as it is compatible with BLtouch connections.
* Support Can bus module
### Hardware Version
 . | hardware | firmware
--- | --- |---  
2022.6 | BDsensor VA, V1.0 | V1.0  
2023.4 | BDsensor VB, V1.1, changed the connector | V1.1, support self reboot
2023.11 | BDsensor VB, V1.3, changed the MCU inside to stm32 | V1.2, firmware for stm32

### Software
 . | Marlin | Klipper
--- | --- |---  
Real Time leveling |:heavy_check_mark:| :heavy_check_mark:  
Fast bed mesh |:heavy_check_mark:| :heavy_check_mark: 
Fast bed mesh(No toolhead stop)|:heavy_check_mark: | :heavy_check_mark: 
Distance display |:heavy_check_mark: | :heavy_check_mark: 
Can bus toolhead|No | :heavy_check_mark: 
standby mode automatic while printing|:heavy_check_mark: | :heavy_check_mark: 
[KAMP](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging) Adaptive Meshing & Purging |No | :heavy_check_mark: 


#### Installation: [Marlin](https://github.com/markniu/Bed_Distance_sensor/wiki/Installing-Bed-Distance-Sensor) | [Klipper](https://github.com/markniu/Bed_Distance_sensor/wiki/Installing-for-Klipper) 
#### Mount STL:  [BLtouch_Compatible](https://www.thingiverse.com/thing:6098131) | [VzBoT](https://discord.com/channels/829828765512106054/1163237892957671424)

#### Test Video: [RealTime adjust test ](https://www.youtube.com/watch?v=yx8pluEu0sg)| [JY-310 3D printer](https://www.youtube.com/clip/UgkxrPdIjlBsYOzUNraIL7HPizCh1WwQllYl) |[VzBot Test video](https://www.youtube.com/watch?v=zmtMjwy1y7U) | [Chris's Basement](https://youtu.be/VDOYYskbxV8?si=JiqrQFHsZcs2zIcD)
 
[Project status](https://hackaday.io/project/185096-0006mm-distance-resolution-sensor-for-3d-printer)

#### Where to buy:
 [pandapi3d.com](https://www.pandapi3d.com/bdsensor) , [淘宝店](https://item.taobao.com/item.htm?spm=a1z10.1-c.w4004-14344044600.5.60a16ff77NRBL5&id=684572042388)

 

