# Awesome Robot Operating System 2 (ROS 2) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/fkromer/awesome-ros2/master/ros_logo.svg?sanitize=true" align="right" width="86">](https://github.com/ros2/ros2/wiki)

> A curated list of awesome Robot Operating System Version 2.0 (ROS 2) resources and libraries.

## Contents

- [Packages](#packages)
- [Operating systems](#operating-systems)
- [Documentation](#documentation)
- [Community](#community)
- [Books](#books)
- [Courses](#courses)
- [Presentations](#presentations)
- [Papers](#papers)
- [Podcasts](#podcasts)

## Packages

### Demostrations

- [adlink_ddsbot](https://github.com/Adlink-ROS/adlink_ddsbot) - The ROS 2.0/1.0 based robots swarm architecture (opensplice DDS) ![adlink_ddsbot](https://img.shields.io/github/stars/Adlink-ROS/adlink_ddsbot.svg).
- [adlink_neuronbot](https://github.com/Adlink-ROS/adlink_neuronbot) - ROS2/DDS robot pkg for human following and swarm ![adlink_neuronbot](https://img.shields.io/github/stars/Adlink-ROS/adlink_neuronbot.svg).
- [turtlebot3](https://github.com/ROBOTIS-GIT/turtlebot3/tree/ros2) - ROS2 based TurtleBot3 demo including Bringup, Teleop and Cartographer ![turtlebot3](https://img.shields.io/github/stars/ROBOTIS-GIT/turtlebot3.svg).

### Examples

- [turtlebot2_demo](https://github.com/ros2/turtlebot2_demo) - TurtleBot 2 demos using ROS 2 ![turtlebot2_demo](https://img.shields.io/github/stars/ros2/turtlebot2_demo.svg).
- [examples/rclcpp](https://github.com/ros2/examples/tree/master/rclcpp) - C++ examples ![ros2/examples](https://img.shields.io/github/stars/ros2/examples.svg).
- [examples/rclpy](https://github.com/ros2/examples/tree/master/rclpy) - Python examples ![ros2/examples](https://img.shields.io/github/stars/ros2/examples.svg).
- [rcljava_examples](https://github.com/esteve/ros2_java_examples/tree/master/rcljava_examples) - Package containing examples of how to use the rcljava API ![ros2_java_examples](https://img.shields.io/github/stars/esteve/ros2_java_examples.svg).
- [ros2_talker_android, ros2_listener_android](https://github.com/esteve/ros2_android_examples) - Example Android apps for the ROS2 Java bindings ![ros2_android_examples](https://img.shields.io/github/stars/esteve/ros2_android_examples.svg).

### Benchmarking

- [ros2_benchmarking](https://github.com/piappl/ros2_benchmarking) - Framework for ROS2 benchmarking. ROS2 communication characteristics can be evaluated on several axes, quickly and in an automated way ![ros2_benchmarking](https://img.shields.io/github/stars/piappl/ros2_benchmarking.svg).
- [performance_test](https://github.com/ApexAI/performance_test) - Test performance and latency of various communication means like ROS 2, FastRTPS and Connext DDS Micro ![performance_test](https://img.shields.io/github/stars/ApexAI/performance_test.svg).

### Containerization

- [docker-ros2-ospl-ce](https://github.com/Adlink-ROS/docker-ros2-ospl-ce) - A dockerfile to build a ROS2 + OpenSplice CE container ![docker-ros2-ospl-ce](https://img.shields.io/github/stars/Adlink-ROS/docker-ros2-ospl-ce.svg).
- [ros2_java_docker](https://github.com/esteve/ros2_java_docker) - Dockerfiles for building ros2_java with OpenJDK and Android ![ros2_java_docker](https://img.shields.io/github/stars/esteve/ros2_java_docker.svg).
- [microROS/docker](https://github.com/microROS/docker) - Docker-related material to setup, configure and develop with micro-ROS hardware.

### Ecosystem

- [rosbag2](https://github.com/ros2/rosbag2) - ROS2 native rosbag ![rosbag2](https://img.shields.io/github/stars/ros2/rosbag2.svg).
- [rviz](https://github.com/ros2/rviz) - 3D Robot Visualizer ![rviz](https://img.shields.io/github/stars/ros2/rviz.svg).
- [urdfdom](https://github.com/ros2/urdfdom) - URDF (U-Robot Description Format) library which provides core data structures and a simple XML parser ![urdfdom](https://img.shields.io/github/stars/ros2/urdfdom.svg).
- [urdfdom_headers](https://github.com/ros2/urdfdom_headers) - Headers for URDF parsers ![urdfdom_headers](https://img.shields.io/github/stars/ros2/urdfdom_headers.svg).
- [ros2cli](https://github.com/ros2/ros2cli) - ROS 2 command line tools ![ros2cli](https://img.shields.io/github/stars/ros2/ros2cli.svg).
- [orocos_kinematics_dynamics](https://github.com/ros2/orocos_kinematics_dynamics) - Orocos Kinematics and Dynamics C++ library ![orocos_kinematics_dynamics](https://img.shields.io/github/stars/ros2/orocos_kinematics_dynamics.svg).

### Application layer

- [ros2_control](https://github.com/ros-controls/ros2_control) - `ros2_control` is a proof of concept on how new features within ROS 2 can be elaborated and used in the context of robot control (`ros2_controllers`) ![ros2_control](https://img.shields.io/github/stars/ros-controls/ros2_control.svg).
- [ros2_controllers](https://github.com/ros-controls/ros2_controllers) - Description of ros_controllers ![ros2_controllers](https://img.shields.io/github/stars/ros-controls/ros2_controllers.svg).
- [geometry2](https://github.com/ros2/geometry2) - A set of ROS packages for keeping track of coordinate transforms ![geometry2](https://img.shields.io/github/stars/ros2/geometry2.svg).
- [cartographer](https://github.com/ros2/cartographer) - Real-time simultaneous localization and mapping (SLAM) in 2D and 3D across multiple platforms and sensor configurations ![cartographer](https://img.shields.io/github/stars/ros2/cartographer.svg).
- [vision_opencv](https://github.com/ros2/vision_opencv) - Packages for interfacing ROS2 with OpenCV ![vision_opencv](https://img.shields.io/github/stars/ros2/vision_opencv.svg).
- [teleop_twist_keyboard](https://github.com/ros2/teleop_twist_keyboard) - Generic Keyboard Teleop for ROS2 ![teleop_twist_keyboard](https://img.shields.io/github/stars/ros2/teleop_twist_keyboard.svg).
- [teleop_twist_joy](https://github.com/ros2/teleop_twist_joy) - Simple joystick
  teleop for twist robots ![teleop_twist_joy](https://img.shields.io/github/stars/ros2/teleop_twist_joy.svg).
- [navigation](https://github.com/ros2/navigation) - ROS2 Navigation stack ![navigation](https://img.shields.io/github/stars/ros2/navigation.svg).
- [diagnostics](https://github.com/bponsler/diagnostics/tree/ros2-devel) - Forked version of the original ROS1 Diagnostics for ROS 2 (currently diagnostics_updater only) ![diagnostics](https://img.shields.io/github/stars/bponsler/diagnostics.svg).
- [robot_state_publisher](https://github.com/bponsler/robot_state_publisher/tree/publish-robot-model) - Forked version of the original ROS Robot State Publisher with all modifications to compile within a ROS2 Ecosystem ![robot_state_publisher](https://img.shields.io/github/stars/bponsler/robot_state_publisher.svg).
- [common_interfaces](https://github.com/ros2/common_interfaces) - A set of packages which contain common interface files (.msg and .srv) ![common_interfaces](https://img.shields.io/github/stars/ros2/common_interfaces.svg).
- [ros2_object_analytics](https://github.com/intel/ros2_object_analytics) - Object Analytics (OA) is ROS2 wrapper for realtime object detection, localization and tracking ![ros2_object_analytics](https://img.shields.io/github/stars/intel/ros2_object_analytics.svg).
- [ros2_intel_movidius_ncs](https://github.com/intel/ros2_intel_movidius_ncs) - ROS2 wrapper for Movidius™ Neural Compute Stick (NCS) Neuronal Compute API ![ros2_intel_movidius_ncs](https://img.shields.io/github/stars/intel/ros2_intel_movidius_ncs.svg).
- [apriltag2_node](https://github.com/christianrauch/apriltag2_node) - ROS2 node for AprilTag detection ![apriltag2_node](https://img.shields.io/github/stars/christianrauch/apriltag2_node.svg).
- [ros2-web-bridge](https://github.com/RobotWebTools/ros2-web-bridge) - Bridging your browser to the ROS 2.0 ![ros2-web-bridge](https://img.shields.io/github/stars/RobotWebTools/ros2-web-bridge.svg).
- [ros2_message_filters](https://github.com/intel/ros2_message_filters) - ros2_message_filters blends various messages based on the conditions that filter needs to met and derives from ROS2 porting of ROS message_filters ![ros2_message_filters](https://img.shields.io/github/stars/intel/ros2_message_filters.svg).

### "System" bindings

- [rclandroid](https://github.com/esteve/ros2_android/tree/master/rclandroid) - Android API for ROS2 ![rclandroid](https://img.shields.io/github/stars/esteve/ros2_android.svg).
- [rclnodejs](https://github.com/RobotWebTools/rclnodejs) - Node.js version of ROS2.0 client ![rclnodejs](https://img.shields.io/github/stars/RobotWebTools/rclnodejs.svg).
- [riot-ros2](https://github.com/astralien3000/riot-ros2) - This project enables ROS2 to run on microcontrollers using the RIOT Operating System ![riot-ros2](https://img.shields.io/github/stars/astralien3000/riot-ros2.svg).

### Driver layer

- [flock2](https://github.com/clydemcqueen/flock2) - ROS2 driver for DJI Tello drones ![flock2](https://img.shields.io/github/stars/clydemcqueen/flock2.svg).
- [ros2_raspicam_node](https://github.com/Misterblue/ros2_raspicam_node) - ROS2 node for Raspberry Pi camera ![ros2_raspicam_node](https://img.shields.io/github/stars/Misterblue/ros2_raspicam_node.svg).
- [joystick_drivers](https://github.com/ros2/joystick_drivers) - ROS2 drivers for joysticks ![joystick_drivers](https://img.shields.io/github/stars/ros2/joystick_drivers.svg).
- [ros_astra_camera](https://github.com/ros2/ros_astra_camera) - ROS2 wrapper for Astra camera ![ros_astra_camera](https://img.shields.io/github/stars/ros2/ros_astra_camera.svg).
- [ros2_android_drivers](https://github.com/esteve/ros2_android_drivers) - Collection of ROS2 drivers for several Android sensors ![ros2_android_drivers](https://img.shields.io/github/stars/esteve/ros2_android_drivers.svg).
- [ros2_intel_realsense](https://github.com/intel/ros2_intel_realsense) - ROS2 Wrapper for Intel® RealSense™ Devices ![ros2_intel_realsense](https://img.shields.io/github/stars/intel/ros2_intel_realsense.svg).
- [raspicam2_node](https://github.com/christianrauch/raspicam2_node) - ROS2 node for camera module of Raspberry Pi ![raspicam2_node](https://img.shields.io/github/stars/christianrauch/raspicam2_node.svg).
- [HRIM](https://github.com/erlerobot/HRIM) - A standard interface for robot modules.

### Client libraries

- [rclada](https://github.com/ada-ros/rclada) - ROS Client Library for Ada ![rclada](https://img.shields.io/github/stars/ada-ros/rclada.svg).
- [rclcpp](https://github.com/ros2/rclcpp) - ROS Client Library for C++ ![rclcpp](https://img.shields.io/github/stars/ros2/rclcpp.svg).
- [rclpy](https://github.com/ros2/rclpy) - ROS Client Library for Python ![rclpy](https://img.shields.io/github/stars/ros2/rclpy.svg).
- [rcljava](https://github.com/esteve/ros2_java/tree/master/rcljava) - ROS Client Library for Java ![rcljava](https://img.shields.io/github/stars/esteve/ros2_java.svg).
- [rclnodejs](https://github.com/RobotWebTools/rclnodejs) - ROS Client Library for Node.js ![rclnodejs](https://img.shields.io/github/stars/RobotWebTools/rclnodejs.svg).
- [rclobjc](https://github.com/esteve/ros2_objc) - ROS Client Library for Objective C (for iOS) ![rclobjc](https://img.shields.io/github/stars/esteve/ros2_objc.svg).
- [rclc](https://github.com/ros2/rclc) - ROS Client Library for C ![rclc](https://img.shields.io/github/stars/ros2/rclc.svg).
- [ros2_rust](https://github.com/esteve/ros2_rust) - Rust bindings for ROS2 ![ros2_rust](https://img.shields.io/github/stars/esteve/ros2_rust.svg).
- [ros2_dotnet](https://github.com/esteve/ros2_dotnet) - .NET bindings for ROS2 ![ros2_dotnet](https://img.shields.io/github/stars/esteve/ros2_dotnet.svg).

### Client libraries common

- [rcl](https://github.com/ros2/rcl) - Library to support implementation of language specific ROS Client Libraries ![rcl](https://img.shields.io/github/stars/ros2/rcl.svg).
- [system_tests](https://github.com/ros2/system_tests) - Tests for rclcpp and rclpy ![system_tests](https://img.shields.io/github/stars/ros2/system_tests.svg).
- [rcl_interfaces](https://github.com/ros2/rcl_interfaces) - A repository for messages and services used by the ROS client libraries ![rcl_interfaces](https://img.shields.io/github/stars/ros2/rcl_interfaces.svg).

### IDL generators

- [rosidl_generator_java](https://github.com/esteve/ros2_java/tree/master/rosidl_generator_java) - Generate the ROS interfaces in Java ![ros2_java](https://img.shields.io/github/stars/esteve/ros2_java.svg).
- [rosidl_generator_objc](https://github.com/esteve/ros2_objc/tree/master/rosidl_generator_objc) - Generate the ROS interfaces in Objective C ![ros2_objc](https://img.shields.io/github/stars/esteve/ros2_objc.svg).
- [rosidl_generator_cpp](https://github.com/ros2/rosidl/tree/master/rosidl_generator_cpp) - Generate the ROS interfaces in C++ ![rosidl](https://img.shields.io/github/stars/ros2/rosidl.svg).
- [rosidl_generator_c](https://github.com/ros2/rosidl/tree/master/rosidl_generator_c) - Generate the ROS interfaces in C ![rosidl](https://img.shields.io/github/stars/ros2/rosidl.svg).
- [rosidl](https://github.com/ros2/rosidl) - Packages which provide the ROS IDL (.msg) definition and code generation ![rosidl](https://img.shields.io/github/stars/ros2/rosidl.svg).
- [rosidl_dds](https://github.com/ros2/rosidl_dds) - Generate the DDS interfaces for ROS interfaces ![rosidl_dds](https://img.shields.io/github/stars/ros2/rosidl_dds.svg).

### RMW (ROS middleware)

- [rmw](https://github.com/ros2/rmw/tree/master/rmw) - Contains the ROS middleware API ![rmw](https://img.shields.io/github/stars/ros2/rmw.svg).
- [rmw_connext_cpp](https://github.com/ros2/rmw_connext/tree/master/rmw_connext_cpp) - Implement the ROS middleware interface using RTI Connext static code generation in C++ ![rmw_connext_cpp](https://img.shields.io/github/stars/ros2/rmw_connext.svg).
- [rmw_fastrtps_cpp](https://github.com/ros2/rmw_fastrtps/tree/master/rmw_fastrtps_cpp) - Implement the ROS middleware interface using eProsima FastRTPS static code generation in C++ ![rmw_fastrtps_cpp](https://img.shields.io/github/stars/ros2/rmw_fastrtps.svg).
- [rmw_dps](https://github.com/ros2/rmw_dps) - Implementation of the ROS Middleware (rmw) Interface using Intel's Distributed Publish & Subscribe ![rmw_dps](https://img.shields.io/github/stars/ros2/rmw_dps.svg).
- [rmw_opensplice_cpp](https://github.com/ros2/rmw_opensplice/tree/master/rmw_opensplice_cpp) - Implement the ROS middleware interface using PrismTech OpenSplice static code generation in C++ ![rmw_opensplice_cpp](https://img.shields.io/github/stars/ros2/rmw_opensplice.svg).
- [rmw_coredx](https://github.com/tocinc/rmw_coredx) - CoreDX DDS integration layer for ROS2 ![tocinc/rmw_coredx](https://img.shields.io/github/stars/tocinc/rmw_coredx.svg).
- [rmw_freertps](https://github.com/ros2/rmw_freertps) - RMW implementation using freertps ![tocinc/rmw_coredx](https://img.shields.io/github/stars/ros2/rmw_freertps.svg).
- [rcutils](https://github.com/ros2/rcutils) - Common C functions and data structures used in ROS 2 ![rmw](https://img.shields.io/github/stars/ros2/rcutils.svg).
- [freertps](https://github.com/ros2/freertps) - a free, portable, minimalist, work-in-progress RTPS implementation ![rmw](https://img.shields.io/github/stars/ros2/freertps.svg).

### DDS communication mechanism implementations

- [Connext DDS](https://www.rti.com/products/dds) - Connectivity Software for Developing and Integrating IIoT Systems :heavy_dollar_sign: .
- [Fast-RTPS](https://github.com/eProsima/Fast-RTPS) - Implementation of RTPS Standard (RTPS is the wire interoperability protocol for DDS) ![Fast-RTPS](https://img.shields.io/github/stars/eProsima/Fast-RTPS.svg).
- [OpenSplice](https://github.com/ADLINK-IST/opensplice) - Implementation of the OMG DDS Standard ![opensplice](https://img.shields.io/github/stars/ADLINK-IST/opensplice.svg) :heavy_dollar_sign: .
- [CoreDX DDS](http://www.twinoakscomputing.com/coredx) - Implementation of Twin Oaks Computing, Inc. :heavy_dollar_sign: .
- [freertps](https://github.com/ros2/freertps) - A free, portable, minimalist, work-in-progress RTPS implementation ![freertps](https://img.shields.io/github/stars/ros2/freertps.svg).

### Build system (Linux)

- [meta-ros2](https://github.com/erlerobot/meta-ros2) - ROS 2 Layer for OpenEmbedded Linux ![meta-ros2](https://img.shields.io/github/stars/erlerobot/meta-ros2.svg).

### Build system (ROS2)

- [ci](https://github.com/ros2/ci) - ROS 2 CI Infrastructure ![ci](https://img.shields.io/github/stars/ros2/ci.svg).
- [ament_cmake_export_jars](https://github.com/esteve/ros2_java/tree/master/ament_cmake_export_jars) - The ability to export Java archives to downstream packages in the ament buildsystem in CMake ![ros2_java](https://img.shields.io/github/stars/esteve/ros2_java.svg).
- [rmw_implementation_cmake](https://github.com/ros2/rmw/tree/master/rmw_implementation_cmake) - CMake functions which can discover and enumerate available implementations ![rmw](https://img.shields.io/github/stars/ros2/rmw.svg).
- [rmw_implementation](https://github.com/ros2/rmw_implementation) - CMake infrastructure and dependencies for rmw implementations ![rmw](https://img.shields.io/github/stars/ros2/rmw_implementation.svg).

## Operating systems

- [NuttX](https://github.com/microROS/NuttX) - NuttX fork of the official one for use with micro-ROS.
- [RIOT](https://github.com/RIOT-OS/RIOT) - RIOT is a real-time multi-threading operating system (...,) real-time capabilities, small memory footprint, (...) API offers partial POSIX compliance.
- [eMCOS](https://www.esol.com/embedded/emcos.html) - POSIX-compliant real-time OS for many-core processors expected to suppport AUTOSAR in the future.

## Documentation

- [ROS 2 Design](http://design.ros2.org/) - Articles which inform and guide the ROS 2.0 design efforts.
- [ROS 2 Docs (Overview)](http://docs.ros2.org/beta2/index.html#) - Details about ROS 2 internal design and organisation.
- [ROS 2 Tutorials](https://github.com/ros2/ros2/wiki/Tutorials) - Study about ROS2 concept, libraries, build, and development with demoes/examples.
- [ROS 2 Wiki](https://github.com/ros2/ros2/wiki) - Entry point to find all kind of information about ROS 2.
- [ROS 2 Distribution (rosdistro)](https://github.com/ros2/rosdistro) - Info about distributions and the included packages.
- [ROS2 package status (ardent)](http://repo.ros2.org/status_page/ros_ardent_default.html) - Status of ROS2 ardent packages.
- [ROS2 Buildfarm](http://build.ros2.org) - Build information (Jenkins build farm).

## Community

- [ROS Discourse](https://discourse.ros.org/c/ng-ros)
- [ROS Answers](https://answers.ros.org/questions/scope:all/sort:activity-desc/tags:ROS2/)
- [ROS News](http://www.ros.org/news/)
- [ROS Planet](http://planet.ros.org/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/ros2)

## Books

**No books published yet**

## Courses

- [ROS2 How To: Discover Next Generation ROS (Udemy)](https://www.udemy.com/ros2-how-to/)

## Presentations

### ROSCon JP 2018 (english slide presentations only)

- What's next for ROS? (from slide 24 onwards) [Slides](https://roscon.jp/2018/presentations/ROSCon_JP_2018_presentation_2.pdf) [Video](https://vimeo.com/292064161)

### ROSCon 2018

[program announcement](https://roscon.ros.org/2018/#program)

- Hands-on ROS 2: A Walkthrough
- ROS 2 on Autonomous Driving Vehicles
- RViz – The tale of a migration to ROS 2.0
- Launch for ROS 2
- Getting involved in ROS 2 development
- Planning to Plan: Plugins All The Way Down
- Leveraging DDS Security in ROS2
- Arm DDS Security library: Adding secure security to ROS2
- ROS2: Supercharging the Jaguar4x4
- Performance Test - A Tool for Communication Middleware Performance Measuring
- ROS2 for Android, iOS and Universal Windows Platform: a demonstration of ROS2’s portability, and cross-platform and cross-language capabilities
- Integrating ROS and ROS2 on mixed-critical robotic systems based on embedded heterogeneous platforms
- Towards ROS 2 microcontroller meta cross-compilation
- Node.js Client & Web Bridge Ready for ROS 2.0
- RCLAda: the Ada client library for ROS2

### Embedded World Conference 2018 

- ADLink Neuron: An industrial oriented ROS2-based platform [Slides](https://raw.githubusercontent.com/Adlink-ROS/adlink_neuronbot/master/document/ADLINK_NeuronBot_20180313.pdf) [Video](https://www.youtube.com/watch?v=RC6XvTvTs9Y&feature=youtu.be) [Video](https://www.youtube.com/watch?v=qA4_Hmnd_tM&feature=youtu.be)

### 2018

- ROS2 - The Robot Operating System Version 2 (TNG Technology Consulting GmbH) [Slides](https://www.tngtech.com/fileadmin/Public/Images/BigTechday/BTD11/Folien/ROS2.pdf) [Video](https://www.youtube.com/watch?v=6Vzi0Grrlp8)

### ROS Industrial Conference 2017

- micro Robot Operating System: ROS for highly resource-constrained devices [Slides](https://static1.squarespace.com/static/51df34b1e4b08840dcfd2841/t/5a3bb6d524a6947d9d0cbc68/1513862873907/07_Losa.pdf)
- ROS2 - it's coming [Slides](https://static1.squarespace.com/static/51df34b1e4b08840dcfd2841/t/5a3bb787e4966b606fe227d7/1513863070599/11_Thomas.pdf)

### ROSCon 2017

- The ROS 2 vision for advancing the future of robotics development [Slides](https://roscon.ros.org/2017/presentations/ROSCon%202017%20ROS2%20Vision.pdf) [Video](https://vimeo.com/236161417)
- ROS2 Fine Tuning [Slides](https://roscon.ros.org/2017/presentations/ROSCon%202017%20ROS2%20Fine%20Tuning.pdf) [Video](https://vimeo.com/236168591)
- SLAM on Turtlebot2 using ROS2 [Slides](https://roscon.ros.org/2017/presentations/ROSCon%202017%20ROS2%20SLAM.pdf) [Video](https://vimeo.com/236172294)
- Using ROS2 for Vision-Based Manipulation with Industrial Robots [Slides](https://roscon.ros.org/2017/presentations/ROSCon%202017%20ROS2%20Vision-Based%20Manipulation.pdf) [Video](https://vimeo.com/236182180)

### ROS Industrial Conference 2016

- ROS 2.0 AND OPC UA: A STATUS UPDATE [Slides](https://static1.squarespace.com/static/51df34b1e4b08840dcfd2841/t/58235f2eb8a79be587899891/1478713139775/ROS-I-Conf2016-day1-09-keinert.pdf)

### ROSCon 2016

- ROS 2 Update [Slides](https://roscon.ros.org/2016/presentations/ROSCon%202016%20-%20ROS%202%20Update.pdf) [Video](https://vimeo.com/187696091)
- Evaluating the resilience of ROS2 communication layer [Slides](https://roscon.ros.org/2016/presentations/rafal.kozik-ros2evaluation.pdf) [Video](https://vimeo.com/187705229)

### ROSCon 2015

- ROS 2 on “small” embedded systems [Slides](https://roscon.ros.org/2015/presentations/ros2_on_small_embedded_systems.pdf) [Video](https://vimeo.com/142150576)
- State of ROS 2 - demos and the technology behind [Slides](https://roscon.ros.org/2015/presentations/state-of-ros2.pdf) [Video](https://vimeo.com/142151734)
- Real-time Performance in ROS 2 [Slides](https://roscon.ros.org/2015/presentations/RealtimeROS2.pdf) [Video](https://vimeo.com/142621778)

## Papers

- [Open Problems in Robotic Anomaly Detection](https://arxiv.org/pdf/1809.03565.pdf)
- [Towards a distributed and real-time framework for robots: Evaluation of ROS 2.0 communications for real-time robotic applications](https://arxiv.org/pdf/1809.02595.pdf)
- [An information model for modular robots: the Hardware Robot Information Model (HRIM)](https://arxiv.org/pdf/1802.01459.pdf)
- [INTRODUCING THE Robot Security Framework (RSF), A STANDARDIZED METHODOLOGY TO PERFORM SECURITY ASSESSMENTS IN ROBOTICS](https://arxiv.org/pdf/1806.04042.pdf)
- [TOWARDS AN OPEN STANDARD FOR ASSESSING THE SEVERITY OF ROBOT SECURITY VULNERABILITIES, THE ROBOT VULNERABILITY SCORING SYSTEM (RVSS)](https://arxiv.org/pdf/1807.10357.pdf)
- [Robot Operating System 2 - The need for a holistic security approach to robotic architectures](http://journals.sagepub.com/doi/pdf/10.1177/1729881418770011) - Ubuntu 16.04, ROS 2 Beta 2/3, and RTI 5.3 DDS with
DDS Security.
- [Maruyama, Yuya et al. “Exploring the performance of ROS2.” 2016 International Conference on Embedded Software (EMSOFT) (2016): 1-10.](https://www.semanticscholar.org/paper/Exploring-the-performance-of-ROS2-Maruyama-Kato/07b895f3b584dea4f64e91844f243de382026b20)

## Podcasts

- [ROS 2 and DDS for IoT devices with HaoChih Lin (from 5th minute onwards)](http://www.theconstructsim.com/rdp-017-ros-2-dds-iot-haochih/)
- [Everything about ROS 2 with Dirk Thomas (from 16th minute onwards)](http://www.theconstructsim.com/rdp-012-all-about-ros2-with-dirk-thomas/)

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
