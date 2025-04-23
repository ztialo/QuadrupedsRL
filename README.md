Goal: Use RL to make the B1 model walk in the MuJoCo environment

Nautilus SSH key set up:

ssh-keygen -t ed25519 -C "zdli@ucsc.edu”

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519

cat ~/.ssh/id_ed25519.pub

git config --global user.email "zdli@ucsc.edu"
git config --global user.name "Zi Tao Li"




Step 1: Find the B1 URDF for Mujoco

https://github.com/unitreerobotics/unitree_ros/blob/master/robots/b1_description/xacro/b1.urdf

Step 2:
Convert above b1 urdf with gazebo tags to xml file that is mujoco compatible

