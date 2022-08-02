# Catkin Workspace

This is a workspace containing all my ROS1 packages that I use in demos and projects.

## How to create a package in this workspace

Run the `catkin_create_pkg` command with the package name and the depdendencies. The snippet below shows a package called beginner_tutorials with three dependencies: `std_msgs`, `rospy`, and `roscpp`.

```bash
catkin_create_pkg beginner_tutorials std_msgs rospy roscpp
```

## How to use

1. Build the workspace

```bash
cd ~/catkin_ws
catkin_make
```

2. Source the workspace

```bash
. ~/catkin_ws/devel/setup.bash
```
