I used Arduino build 23 to make this.

I wanted to create a code that would allow lady ada's motor shield to be used with a KY-023 analog joystick controller. 
The joystick has a x axis and a y axis. I only used the Y axis to move forward and backward using the joystick. 
the x axis is not being used in this demo. In the future I would like to use the x axis to control a servo for steering. 
The joystick's resistance is 500 in the center, 1024 when pushed all the way up and 0 when pushed all the way down.
I wanted the motor value to be 255 when pushing the joystick to 1024, the motor value to be 255 when pushing the joystick to 0, and I wanted the motor value to be 0 when leaving the joystick at 500.   
using some math i was able to create this effect. 
so this will eventually be a building block to create a wireless RC car.

Edit: the first one is using float() to calculate values and (2) is using map(). float() uses more processing power so map() is a better choice.

send ques to my email
watch81@gmx.com
