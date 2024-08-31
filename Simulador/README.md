# Simulador de robot de servicio y ambiente doméstico usando Gazebo y ROS
Simulador desarrollado como parte del proyecto PAPIME PE105524.

## Requerimientos

* Ubuntu 20.04 https://releases.ubuntu.com/focal/ubuntu-20.04.6-desktop-amd64.iso
* ROS Noetic http://wiki.ros.org/noetic/Installation/Ubuntu

## Instalación

Nota: se asume que ya se tiene instalado Ubuntu y ROS.

* $ cd
* $ git clone https://github.com/mnegretev/PAPIME-PE105524
* $ cd PAPIME-PE105524/Simulador
* $ ./Setup.sh
* $ cd catkin_ws
* $ catkin_make -j2 -l2
* $ echo "source ~/PAPIME-PE105524/Simulador/catkin_ws/devel/setup.bash" >> ~/.bashrc
* $ source ~/.bashrc

## Pruebas

Para probar que todo se instaló y compiló correctamente:

* $ cd 
* $ source PAPIME-PE105524/Simulador/catkin_ws/devel/setup.bash
* $ roslaunch surge_et_ambula movement_planning.launch

Si todo se instaló y compiló correctamente, se debería ver un visualizador como el siguiente:
![rviz](https://github.com/mnegretev/Mobile-Robots-2025-1/blob/main/Media/rviz.png)

Un ambiente simulado como el siguiente:
![gazebo](https://github.com/mnegretev/Mobile-Robots-2025-1/blob/main/Media/gazebo.png)

Y una GUI como la siguiente:
![GUIExample](https://github.com/mnegretev/Mobile-Robots-2025-1/blob/main/Media/gui.png)

## Contacto
Dr. Marco Negrete<br>
Profesor Asociado C<br>
Departamento de Procesamiento de Señales<br>
Facultad de Ingeniería, UNAM <br>
marco.negrete@ingenieria.unam.edu<br>
