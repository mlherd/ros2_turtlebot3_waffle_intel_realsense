# ros2_turtlebot3_waffle_intel_realsense
Gazebo model for Turtlebot 3 Waffle robot with Intel RealSense Camera with ROS2 plugins.

- RGB Image
- Depth Image
- Point Cloud

Tested using Gazebo 9 and ROS2 Dashing.

# RealSense Camera Topic Names

- /intel_realsense_r200_depth/camera_info_raw
- /intel_realsense_r200_depth/depth/camera_info
- /intel_realsense_r200_depth/depth/image_raw
- /intel_realsense_r200_depth/image_raw
- /intel_realsense_r200_depth/points
- /intel_realsense_r200_rgb/camera_info
- /intel_realsense_r200_rgb/image_raw

# Camera Frame Names: 

- realsense_depth_frame
- raelsense_rgb_frame

## Turtlebot 3 with Intel RealSense in Turlebot World in Gazebo
![gz_realsense.png](https://raw.githubusercontent.com/mlherd/ros2_turtlebot3_waffle_intel_realsense/master/pics/gz_realsense.png)

## Point Cloud view in Rviz
![gz_realsense.png](https://raw.githubusercontent.com/mlherd/ros2_turtlebot3_waffle_intel_realsense/master/pics/rviz_point_cloud.png)
