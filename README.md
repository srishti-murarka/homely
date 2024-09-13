# Homely: A Smart-Home System
## Project Overview
In this project, a smart home with different sensors like  a Smoke Detector, PIR, Ultrasonic distance sensor and LDR sensor was built. All these sensors are connected to an Arduino.

![view](https://user-images.githubusercontent.com/97884235/178325247-a852acca-b953-43cc-8fe8-7b165cdba87c.png)

## Components Used
<ul>
  <li>Arduino</li>
  <li>Smoke detector MQ6</li>
  <li>PIR</li>
  <li>LDR</li>
  <li>Ultrasonic Distance Sensor</li>
  <li>Piezo buzzer</li>
  <li>DC power source(Any 12V)</li>
  <li>Relay boards of 2 channels </li>
</ul>


## Functionalities
### Ultrasonic Distance sensor

This is a sensor that detects a person at a certain distance in its range. Whenever it detects a human, it automatically opens the door using a servo motor.

![uds off](https://user-images.githubusercontent.com/97884235/178325344-c7f2d5ec-7ce6-45b4-ad6c-2114ebea1339.png)

When the person crosses this distance the servo motor is reset to its original position and the door is closed.

![uds](https://user-images.githubusercontent.com/97884235/178325303-2b3010ce-074a-4500-8252-ae0e22f755a2.png)

### PIR sensor

This is a sensor that detects humans in its surrounding region and will turn on the fan(which runs by a motor).

![pir on](https://user-images.githubusercontent.com/97884235/178325566-b2eafaf5-01ca-47a4-9350-ecbeff7769e1.png)

When the person goes out of its range it will turn off the fan after a few seconds.

![pir sensor](https://user-images.githubusercontent.com/97884235/178325683-6a1b2e60-4607-42f4-bd06-7d01811d4262.png)
Here the fan can also be controlled manually in our design using a slide-switch attached to it.

### LDR sensor

This is a sensor which helps us to turn on the lights in the dark or at night time. It will detect the brightness of surroundings and whenever it detects a human it will turn lights ON if it's dark.

![bulb](https://user-images.githubusercontent.com/97884235/178326185-30a5165f-abeb-425d-8f98-b43352ae4156.png)

When it's day-time, it detects high brightness and switches off the lights.

![bulb off](https://user-images.githubusercontent.com/97884235/178326324-73c2487f-b1ec-4e2d-acdf-f113c49f78bf.png)

### Smoke Detector
This is a sensor that is connected to a piezo buzzer. When it detects LPG gas around it, the buzzer starts ringing as a caution.

![lpg off](https://user-images.githubusercontent.com/97884235/178326787-6d31dd6c-ff8d-43f3-a144-d46f2c70c92d.png)

![gas on](https://user-images.githubusercontent.com/97884235/178326726-ea3fa240-9d80-4e44-81ce-c84ff7203778.png)

This project is implemented on the Tinkercad platform. The link is attached here--> https://www.tinkercad.com/things/5ZAtoNRIAgA-smart-home/editel?sharecode=0i3DThz9vrst6QQv6TAdRgu2PVwnbKovvfFmOq7b-3I
