# kuka_kr150
This is a package for simulation of KUKA KR150 using ROS.

## How to Use
To startup Gazebo and spawn KUKA KR150 3d model:  
`roslaunch kuka_kr150_gazebo test_kr150_gazebo.launch`

To plan and execute:  
`roslaunch kuka_150_moveit_config moveit_planning_execution.launch`

rqt_graph after the aboves are launched:
![rqtgraph](rosgraph_2018-06-12.png)

Videos:
![video](rviz_2018-06-12.gif)
![video](gazebo_2018-06-12.gif)
