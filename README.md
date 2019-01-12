# MQTT Sonoff Devices
This code includes use cases for garage door openers, door sensors, and other Sonoff projects.

## 1. Use Cases ##
- A smart wireless mqtt door sensor
- A smart garage


## 2. Gear ##
- Wired Door Sensor Magnetic Switch - https://amzn.to/2AyoREm
- HiLetgo ESP8266 NodeMCU - https://amzn.to/2CRJTPK
- Sonoff SV - https://amzn.to/2VqgKSW
- 3.3V 5.5V FT232RL FTDI USB to TTL Serial Adapter - https://amzn.to/2R7VdQo
- Cheap 97 cents soap box from Walmart
- jumper wire kit
- Glue Gun

## 3. Code ##

### 

## Reference to The HookUp YouTube channel that got me started
https://www.youtube.com/watch?v=xCQoOZNdaGY


## DEVICE CLASS ##
#### The way these sensors are displayed in the frontend can be modified in the customize section. The following device classes are supported for binary sensors: ####

None: Generic on/off. This is the default and doesn’t need to be set.__
battery: On means low, Off means normal__
cold: On means cold, Off means normal
connectivity: On means connected, Off means disconnected
door: On means open, Off means closed
garage_door: On means open, Off means closed
gas: On means gas detected, Off means no gas (clear)
heat: On means hot, Off means normal
light: On means light detected, Off means no light
lock: On means open (unlocked), Off means closed (locked)
moisture: On means moisture detected (wet), Off means no moisture (dry)
motion: On means motion detected, Off means no motion (clear)
moving: On means moving, Off means not moving (stopped)
occupancy: On means occupied, Off means not occupied (clear)
opening: On means open, Off means closed
plug: On means device is plugged in, Off means device is unplugged
power: On means power detected, Off means no power
presence: On means home, Off means away
problem: On means problem detected, Off means no problem (OK)
safety: On means unsafe, Off means safe
smoke: On means smoke detected, Off means no smoke (clear)
sound: On means sound detected, Off means no sound (clear)
vibration: On means vibration detected, Off means no vibration (clear)
window: On means open, Off means closed
