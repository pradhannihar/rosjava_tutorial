# rosjava_tutorial



to start the tutorial follow the steps:

1.assume that rosjava has been install completely.....

2.create a package inside the src folder of your ros java workpace by "catkin_create_rosjava_pkg <package name>"
  
3.create a project inside the your <package name> folder by "catkin_create_rosjava_project <project name>"
  
  
  by default the abve process will reate "Talker.java" and "Listener.java" file with code so no need to change any file....
  
4.go to ur rosjava workpace and source the setup file present in devel e.g. $ source devel/setup.bash

5.run catkin_make and wait if it download the gradle file it will get downloaded once......


6.go to ur <packge name> directory and $ source /opt/ros/<ur ros distro name>setup.bash and  source the setup file present in devel 
7.run $ ./gradlew install from ur package directory
  
8.running the node 

--> first run roscore by sourcing the setup e.g. $ source devel/setup.bash

-->go to project directory and run  


./build/install/<project name>/bin/<project name> com.github.rosjava.<package name>.<project name>.Talker
  
./build/install/<project name>/bin/<project name> com.github.rosjava.<package name>.<project name>.Listener
  
  
  
  reference __
  http://visionlab.uncc.edu/dokuwiki/rosjava
