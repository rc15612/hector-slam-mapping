# hector-slam-mapping
1.download and install the EAIBOT ROS package :  
git clone https://github.com/EAIBOT/ydlidar.git  
catkin_make

2.create all_node.launch in the same workspace and then source

3.roslaunch ydlidar all_node.launch

4.click on add button in rviz menu. select by topic button and select /map from it.

5.move ydlidar to build your map 

6.to save the map you just created : rosrun map_server map_saver -f /tmp/my_map

![image](https://github.com/yu-yung/hector-slam-mapping/blob/master/map0508.PNG)

