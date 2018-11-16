#
## IOT Product Power Consumption Tuning

## Key Points
+ Physical sensors powered control.
+ Physical sensors accessing time(hardware interruption/spi/i2c)
+ Microcontroller processing time.

## IOT Product hardware architecture

<img src="hardware_archieture.png"
width="100%"
height="1000%"
alt="Hardware architecture"
align=center />

## Turning Method
+ Power Meter

Monitored physical sensors current consumption.

<img src="peripheral_communication_active.png"
width="100%"
height="1000%"
alt="periphreal consumed state with microcontroller was be wakeup via MEMS sensors"
align=center />

<img src="peripheral_communication_suspended.png"
width="100%"
height="1000%"
alt="periphreal consumed state with microcontroller was be in suspended state"
align=center />

Monitored microcontroller current consumption.

<img src="microcontroller_active.png"
width="100%"
height="1000%"
alt="microcontroll active current consumption"
align=center />

<img src="microcontroller_suspended.png"
width="100%"
height="1000%"
alt="microcontroll suspended current consumption"
align=center />

+ Logical analyzer

Microcontroller sleeping and active duration.
<img src="iotmcuactive.png"
width="100%"
height="1000%"
alt="microcontroll active process"
align=center />

What kind of jobs were be executed in microcontroller active duration.
<img src="iotmcuactive_sleeping.png"
width="100%"
height="100%"
alt="microcontroller active and sleeping duration"
align=center />


