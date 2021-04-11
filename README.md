# turtlebot_gazebo_octomapping

### Turtlebot3 has 3 models [burger, waffle, waffle_pi].\
### waffle_pi urdf file has been edited in which all sensors has been removed. So use only "waffle" 

## How To Run

### Terminal 1:-
```bash
export TURTLEBOT3_MODEL="waffle"
roslaunch turtlebot3_gazebo turtlebot3_world.launch
```


### Terminal 2:-
```bash
export TURTLEBOT3_MODEL="waffle"
roslaunch turtlebot3_gazebo turtlebot3_gazebo_rviz.launch
```


### Terminal 3:-
```bash
export TURTLEBOT3_MODEL="waffle"
roslaunch turtlebot3_example octomap_turtlebot.launch
```

### Terminal 4:-
```bash
export TURTLEBOT3_MODEL="waffle"
roslaunch turtlebot3_gazebo turtlebot3_simulation.launch
```
