# ROS2-HTTP Server - For ROS2 DataSet storage (rclcpp)

## Document
  - [Environment](#environment)
  - [Installation](#installation)
    - [Prerequisites](#prerequisites)
    - [Colcon Build](#clone--colcon-build)
    - [Run Test](#run-test)

## Environment
* <img src="https://img.shields.io/badge/cpp-magenta?style=for-the-badge&logo=cplusplus&logoColor=white">
* <img src="https://img.shields.io/badge/cmake-064F8C?style=for-the-badge&logo=cmake&logoColor=white">
* <img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white">
* <img src="https://img.shields.io/badge/ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white">

## Installation

### Prerequisites
- [ROS2 setup](https://index.ros.org/doc/ros2/Installation/) for install rclc -
  **INSTALL [ROS2 Foxy-Fitzroy](https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html)**

### Clone & Colcon Build
```bash
source /opt/ros/foxy/setup.bash
git clone https://github.com/reidlo5135/rclcpp_http_server.git
cd rclcpp_http_server
colcon build --symlink-install
source install/setup.bash
```

### Run Test
```bash
source rclcpp_http_server/install/setup.bash
ros2 run rclcpp_http_server ros_http_server
```