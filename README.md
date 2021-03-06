# Workaround to use soft body simulation with ROS

Commands to run:

        roscore
        rostopic echo /test_msg
        cd $HOME/ros_ws/april_pybullet_ws/src/bullet3/build/devel/lib/BULLET_PHYSICS
        ./App_ExampleBrowser

Expected result:

        data: "Hello, I am Pinch"

To build:

        cd $HOME/ros_ws/april_pybullet_ws/src/bullet3/build
        make

To build first time:

        mkdir build
        cd build
        cmake ..
        make
