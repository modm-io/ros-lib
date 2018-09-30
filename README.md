# ROS Library for modm

Repository of generated messages headers for rosserial.

Normally, a cron job at GitLab's CI updates this repository. If more message headers are required the ROS package can be added to `package.list`. The CI will then check in the generated files afterwards.

These files can be generated manually with `./rosserial_mbed/src/rosserial_mbed/make_libraries.py` from `jade-devel` branch in rosserial.
