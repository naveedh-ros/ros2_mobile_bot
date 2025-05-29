ROS2 Mobile Robot with Manipulator – Simulation Project
This repository contains a ROS2-based mobile robot project simulated in Gazebo. The robot is designed with a differential-drive mobile base and is being extended with a manipulator arm and onboard camera system.

🚀 Features
ROS2 Humble-based simulation

Differential drive mobile base

Real-time simulation in Gazebo

Camera module integrated and streaming in RViz

🦾 In Progress
2-DOF Manipulator Arm: Currently being modeled and integrated into the simulation.
OpenCV integration

📁 Structure
bash
Copy
Edit
ros2_ws/
└── src/
    ├── my_robot_description/    # URDF, meshes, Xacro files
    ├── my_robot_bringup/        # Launch files
    └── my_robot_control/        # (Upcoming) Controllers for arm + mobile base
🧠 Goal
This is part of my self-driven journey to master robotics simulation with ROS2. 
The project will serve as a base for advanced applications like perception, manipulation, and autonomous navigation.

📍Next Steps
Finish and test manipulator simulation

Integrate simple motion planning with ROS2 control

Document everything with visuals and demos

