# BloX Robot-Localization

The BloX Robot-Localization implements sensor fusion and robot localization based on the ROS2 version of the [robot_localization](https://github.com/cra-ros-pkg/robot_localization) package. The package's official documentation and how to configure it can be found [here](http://docs.ros.org/en/noetic/api/robot_localization/html/index.html).

## Data

Depending on the configuration in config.yaml, the BloX Robot-Localization subscribes to sensor messages from various sensors, e.g. IMU, GNSS, wheel odometry, and publishes coordinate transforms, i.e. tf2 message of the specified frames, e.g. odom->robot_base or world->odom. 
