# haruto-msgs
Repo for customized ros messages 

## Command msg
PWM signal to be sent to Motor driver for controller the speed. Recieved by arduino controller

## Encoder msg 
Feedback to be recieved from Arduino controller. Ticks counted from encoders on all four motors 

## Pid msg
PID parameters for error correction on four motors of the robot (Managed at ROS level)

## Velocity msg
Feedback information of expected and actual velocities
