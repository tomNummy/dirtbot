# dirtbot
dirtbot helps with indoor gardening autmation. Now with 100% more dirt!

## General Plan
Run home assistant on a Raspberry pi 4 to that will monitor and control environmental conditions.
Raspberry pi is set up 

### V0
Read Only mode
- Temp
- Humidity
- Pressure
These can all be read from the portable weather station via the sdr
Goal is to get familiar with home assistant and get the database up and running, make some nice graphana dashboards.

### V1
Controlling
- Light
- Ventilation
- Temperature + Light (Bedroom wake up routine)
These can be controlled via smart plugs.
Goal here is to get the tent on a good light and ventilation schedule.

### V2
Monitor soil moisture
    - send an alert when moisture is too low
Webcam
    - Takes periodic photos of the grow tent

### V3
Irrigation
- Add a water source that can be pumped into the beds when soil moisture is too low
    - This is scary... I would want to add a leak detection system to shut things off
