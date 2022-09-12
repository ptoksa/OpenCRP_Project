# OpenCRP Project

Many of the work processes and tasks demand great precision, error-free operations and high quality outcomes. Humans are not at their best
in these actions. Due to this human frailty, many duties can be assigned to be carried out by automatized platforms. Healthcare and hospice
operations retain processes, which can be assisted by mobile robots. The service architecture model developed in Tampere University of
Technology, Pori, consists of a novel mobile cloud robotic platform in the supporting of patient work. The developed ecosystem, OpenCRP,
holds an open-source cloud computing platform, software frameworks and a physical multi-robot environment for the automation or assisting of
preprogrammed work processes.

Mobile robots with service-oriented functions are stepping to our lives in hospitals, hospices and industries where robots can help to assist or
perform all the arduous working duties. A lot of laborious processes can be identified that can be automatized, e.g. in hospital medicine delivery and
food servery to ward for patients. The service architecture model presents a pilot- and demonstration environment for multiple open-source mobile
robots sharing their collected data with each other via a private cloud. In addition, the presented platform introduces a novel ecosystem based on an
open-source software frameworks and robots.

## Research Outcome
The Open Cloud Robotic Platform project (OpenCRP) at the Tampere University of Technology aims to gather information and increase the knowledge on using open source mobile robots and cloud services in a multirobot ecosystem. The project includes implementation of a demonstration/pilot environment as well as its examination. When proceeding deeper into the research we found that ROS 2 (Robot Operating System 2) will have simpler implementation of the multirobot feature than ROS 1 has. We became convinced that it is worth waiting for a more mature ROS 2 release and implement the mul-
tirobot environment when the upgrade to ROS 2 becomes worthwhile. This phase covers only an implementation of a single robot environment with a controlling user interface and a cloud service as a map storage. Features of the environment are examined.

We had two Turtlebot II robot development kits available. Both of the robots were equipped with 3D sensors, one with a Kinect Xbox 360 and the other with an Xtion Pro Live. To drive the robots, two laptop computers were prepared by installing ROS Indigoand Hadoop 2.7.2 software on their Ubuntu 14.04 platforms. Laptops were placed on top of the robots and attached to them via USB connections. To control a robot remotely, ROS was installed into two other computers as well. Also, Hadoop was installed into these remote computers and they were configured as a two computer HDFS-cluster. The
cluster served as a map storage and could be used from the robots with terminal commands. Remote computers were also configured to have MapReduce available for possible usage in the future. For robot controlling purposes a simple UI was implemented with Qt. With the UI in one or more of the computers, a robot can be driven to desired map positions by press of a button. A WLAN was used to connect the robot’s laptop to the remote computers and its mapping and navigation capabilities were tested. Both 3D sensors’ observation ranges were measured and the adequacy of a WLAN connection of ro
bot’s computer was evaluated.

The result we achieved was a fully functional open source mobile robot environment, where the maps could be stored into and fetched from a Hadoop cloud service. A robot could be controlled via implemented UI avoiding obstacles on its path. We gained a lot of knowledge about implementing an OpenCRP environment in practise and the challenges of the implemented environment. Many possibilities for improving the functionality of the environment arose. The two most important would be improving the near range obstacle observation capabilities and the quality of wireless connection.

ERDF page: https://www.eura2014.fi/rrtiepa/projekti.php?projektikoodi=A71334

Project video trailer:
https://www.youtube.com/watch?v=dmaXas1CMf0
* GUI built with ros.org template
* TurtleBot robot run by using the previously gmapped environment
* Dynamic obstacle avoiding demonstrated
