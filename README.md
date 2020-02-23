# Udacity Self Driving Car ND Capstone Project

Team Members:
* Igor Aranovsky ( igor.aranovsky@accenture.com )
* Ryan Kopec ( yankopec91@gmail.com ) 
* Zhenhao Xu ( xuzhenghao0502@163.com )
* Sandeep Gholap ( frnd.sandeep@gmail.com )
* Holger Wienecke ( holger.wienecke@accenture.com )

## System / Code Structure

![System Overview](imgs/final-project-ros-graph-v2.png "System Overview")

## Usage

### Clone & configure the Repository

1. Clone the project repository
```bash
git clone https://github.com/udacity/CarND-Capstone.git
```

2. Install python dependencies
```bash
cd CarND-Capstone
pip install -r requirements.txt
```
If the pip command fails, retry with
```
pip install -r requirements.txt --no-cache
```

### Build the Software

1. Use the catkin_make command to build the Catkin Workspace
```bash
cd ros
catkin_make
```

### Run the Software
1. Enable the environment
```bash
source devel/setup.sh
```
2. Launch the Software
```bash
roslaunch launch/styx.launch
```

3. Run the simulator

### Real world testing
1. Download [training bag](https://s3-us-west-1.amazonaws.com/udacity-selfdrivingcar/traffic_light_bag_file.zip) that was recorded on the Udacity self-driving car.
2. Unzip the file
```bash
unzip traffic_light_bag_file.zip
```
3. Play the bag file
```bash
rosbag play -l traffic_light_bag_file/traffic_light_training.bag
```
4. Launch your project in site mode
```bash
cd CarND-Capstone/ros
roslaunch launch/site.launch
```
5. Confirm that traffic light detection works on real life images



## Simulator Run

Please click to see a prerecorded simulator run:
[![Simulator Run](http://img.youtube.com/vi/9dm-qnZ3Fpo/0.jpg)](http://www.youtube.com/watch?v=9dm-qnZ3Fpo "Simulator Run")


