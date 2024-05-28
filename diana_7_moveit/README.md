## diana7_description

## 编译
```bash
mkdir -p ~/Diana_7_ros2_ws/src
cd ~/Diana_7_ros2_ws/src
git clone **
cd ..
colcon build 
source ./install/setup.bash
ros2 launch diana_7_moveit demo.launch.py

```
## 依赖
```bash
sudo apt-get install ros-humble-moveit
sudo apt-get install ros-humble-joint-state-publisher-gui
sudo apt-get install ros-humble-ros-controllers
```
## 示意
<img src="https://github.com/rocos-sia/Diana_7_ros2/blob/main/Figures/diana_7_moveit.png" alt="show" />