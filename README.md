# IoTWorkshop

This is a series of three hands on workshops I created for the general public. We create an Arudino based IoT "thing" with wifi connection, and connect a strip of addressable LEDs. We control the LEDs from the cloud, experiment with advanced control using NodeRED, react to data eg Twitter and Push notifications and finally get our "thing" to send data back up to the cloud where we can take action and send commands back to the "thing".

I have run these fortnightly in Brighton. The first takes approx 2.5 hours, the second 2 hours and the third 1- 1.5 hours.

The attendee is given an ESP8266 device, a strip of LEDs and a jumper cables for the duration of the course.

## Content

### Session 1
Overview of IoT
Laptop setup/software and driver installation.
Crearing an IBM Cloud account and "IoT Starter kit" which consists of an instance of NodeRED and an instance of the Watson IoT Platform service in the cloud.
Uploading code to the ESP8266
Connecting the ESP8266 to wifi and the IoT Platform
Sending a command from the cloud to the ESP8266 via the Watson IoT Platform.

### Session 2
A guided intro to NodeRED (mostly reusing the concepts from the excellent official NodeRED documentation).
We do some advanced control of the LED strip which allows us to review the Ardino code we uploaded as well and see how the IoT platform works.
We take a little look at controlling the LED stip connected to out "thing" using exteral data eg Twitter and mobile push notifications.

### Session 3
Sending data from the thing to the cloud via the IoT platform.
Update the Arduino code to send (publish) data to the IoT platform.
Create a NodeRED flow to handle recieveibg and sendind data from/to the thing.
Look at the Dashboard nodes in NodeRED and create a simple mobile interface.
Time to go over attendees projects if they have anything in mind.
