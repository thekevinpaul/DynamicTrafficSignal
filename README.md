# Dynamic Traffic Signal: Smart Traffic Management System.
A Dynamic Traffic Signal generator working on basis of vehicular lane density and assigns signal priority accordingly.


The Dynamic Traffic Signal Generator is an application which senses vehicular lane density and uses an algorithm to assign traffic priority based on a weighted threshold.

A Graphical UI is created as a prototype to test this.

![Smart Traffic Management System](https://github.com/thekevinpaul/DynamicTrafficSignal/blob/main/Output%20Screenshots/ReadMe1.png)


## PreTrained Model Used:
- SSD Model is used, along with label.txt to initiate boundary boxes to detect cars, bikes and vehicles each assigned with a transitory weight which averages the vehichular lane sum to a mean threshold.
![Boundary Boxes for Lane Density](https://github.com/thekevinpaul/DynamicTrafficSignal/blob/main/Output%20Screenshots/north_bbox.png)

# Graphical User Interface Application
Modelled into a GUI which runs through a python script (GUI.py), it analyzes vehicular lane density and assigns traffic signal based on priority decision algorithm.
![GUI](https://github.com/thekevinpaul/DynamicTrafficSignal/blob/main/Output%20Screenshots/2.png)
