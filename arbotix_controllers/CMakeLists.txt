cmake_minimum_required(VERSION 2.8.3)
project(arbotix_controllers)

find_package(catkin REQUIRED)
catkin_package()

install(PROGRAMS bin/one_side_gripper_controller.py bin/parallel_gripper_controller.py bin/parallel_single_servo_controller.py
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
