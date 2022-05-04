---
layout: archive
permalink: /projects/
title: ""
date: 2014-06-02T15:05:16-04:00
modified: 2016-01-04T16:38:17-05:00
ads: false
fullwidth: true
tiles: true
feature:
  visible: false
  headline: "Featured Work"
  category: project
---

{{ page.excerpt | markdownify }}

### Bio-inspired Multi Robot Coordination for Effective Material Handling <br>
In this work, a bio-inspired multi-robot coordination algorithm for form closure is formulated. It is implemented on a team of robots to effectively move material to a goal location. An online computed reward function updates the task assignment probability when a specific event is triggered. A decentralized PD controller is used to navigate each robot to a goal position. There is minimal explicit robot communication. Results show that the proposed task allocation algorithm is scalable and works efficiently for any non-circular material with number of vertices, N < 20. Best reliability factor for the algorithm is RF = 0.5958. Maximum position error of centroid of the material corresponding to best RF is 0.036m. PD controller is proven to be stable using Lyapunov analysis. The navigation strategy is validated in simulation and experimentally by three robots collectively transporting a material<br>
:point_right: [*University Project group profile*](http://www.bits-pilani.ac.in/pilani/computerscience/WearablePervasiveNetworkingLaboratory)

### Inverse Kinematic Analysis of Cassie Robot using Radial Basis Function Network <br>
Inverse Kinematics of bipedal humanoid robots remains a challenging problem in robotics and computation, due to high order non-linearity and computation involved in Inverse Kinematics solutions. Also, there are many constraints involved with the various joint parameters which makes their analysis even more complex.
This work attempts to solve the Inverse Kinematics problem of a bipedal humanoid robot, Cassie, using Radial Basis Function (RBF) Networks. This method can also be applied to other higher degrees of freedom serial manipulators. Simulation analyses the results based on size of datasets, data distribution and network parameters. Datasets of size 300k and 1 million, single and multiple hidden layers, equal and random data distribution, different number of neurons in layers and different training functions are considered. The target of limiting the Mean Squared Error (MSE) calculated using the trained model below 0.1 for each joint angle, which is under acceptable limits for practical implementation was successfully achieved. The configurations obtained from the RBF network are simulated and compared with the original input configuration. This is compared visually in MATLAB and the resulting pose of end-effector are similar for both the cases, complementing
the performance obtained for the networks.<br>
:point_right: [*Code/ProjectRepo*](https://prakhar-agarwal.github.io/traffic-qlearning/)

### Monocular Depth Estimation using Transfer Learning <br>
Depth estimation using vision sensors is usually done using stereo cameras so that the two cameras can be used to triangulate the position of a certain point in the environment. However using monocular camera offers benefits like low power consumption, light weight and low cost. Moreover, monocular cameras can also be used for estimating the depth using various monocular cues like defocus, texture variations and gradients, cold/haze, etc. This project focuses on the monocular depth estimation problem and its potential applications in deformable Simultaneous Localization and Mapping (SLAM).
The dense depth map of each pixel is estimated using a single monocular RGB image using a deep learning-based transfer learning approach. Additionally, a transfer learning-based method and an encoder-decoder structure is implemented to solve the monocular depth estimation task. The NYU dataset V2 is used for training the depth estimation models.

### Design and Analysis of Bio-Inspired Tricopter with Delta Manipulator for Industrial Applications <br>
The use of Unmanned Aerial Vehicles (UAV) will play crucial role in industrial upgrading. The use of UAV in industrial production lines will promote the deep integration of multiple technologies such as Internet of Things (IoT), Artificial Intelligence (AI), Big Data, and Mobile Terminals. In Smart Factories the robots are utilized with human interaction. These robots are generally used to automate simple and repetitive task enhancing productivity and reducing costs. However, using robots fixed to the platform have less degrees of freedom to perform certain complex tasks. Since UAV can move in 3 – Dimensional space, using them in production lines will enhance the 3D positioning accuracy. In order to address the issues of productivity in a manufacturing industry, this project introduce a Tricopter with Delta manipulator with following Novel features:
1. The arms of the tricopter are designed taking into National Advisory Committee for Aeronautics (NACA) airfoil recommendations with some modifications.
2. The arms are Bio-Inspired from the Bird Wings.
3. The design of Delta – Manipulator is optimized for maximum reach during manipulation for the tricopter specifications.

### Autonomous Maze Solver Robot<br>
Solve dthe maze problem in robotics using TurtleBot3. The mobile robot avoids obstacles and simultaneously follows the wall and go from one place to another. This is done only by leveraging the data collected from 2D LiDAR sensor.<br>
:point_right: [Source Code](https://github.com/prakhar-agarwal/insights-app)

### Design and Testing of Hydro-pneumatic Suspension System <br>
DRDO Project under the guidance of Dr. Ajith A Babar (Scientist grade E) – Designed and studied hydraulic system used for testing of hydro-pneumatic suspension system used in Advanced Towed Artillery Gun System (ATAGS). This was successfully implemented in DRDO’s first indigenously developed Artillery Gun System.<br>
