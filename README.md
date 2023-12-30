# ros2_ws: Turtle Controller

<p align="center">
<img width="400" alt="Screenshot 2023-12-29 115700" src="https://github.com/toazbenj/ros2_ws/assets/90994176/f9a45fc5-82bf-438b-a17d-ef1f2cb21ce1">
</p>

This is a personal project I took on to get more familiar with Robot Operating System. I wrote several publisher and subscriber nodes to modify the movement behavior of the turtle icon from the ROS demo nodes. The turtle roams around the open window and adjusts its path based on the boundary conditions to avoid hitting the wall. I also wrote a service to change the color of the turtle's path based on what side of the screen it's on. Similiar processes control robots in the field, and here the turtle simulation is a proxy for the actual physical hardware my closed loop controller would be deploying.   
