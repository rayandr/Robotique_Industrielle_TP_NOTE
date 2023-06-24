# Robotique_Industrielle_TP_NOTE

# part 1
Pour installer ce package il faut le cloner dans le dossier src de votre catkin workspace (catkin_ws)


 cd catkin_ws/src

git clone https://github.com/rayandr/Robotique_Industrielle_TP_NOTE.git

catkin build

cd ..

source devel/setup.bash


Pour afficher robot.urdf, dans un terminal taper la commande suivante:

roslaunch urdf_tutorial display.launch model:='$(find ri_arm_description)/urdf/robot.urdf'


# part 2

Apres avoir genere le package de la question 1, pour visualizer:

cd path_vers_catkin_ws/src/package ri_arm_config/launch

roslaunch demo.launch

	
