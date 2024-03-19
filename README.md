<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>Zombie Apocalypse Simulator</h1>

  <h2>Overview</h2>
  <p>This project is a Zombie Apocalypse Simulator implemented in C++. The simulator allows users to specify various parameters such as the duration of the simulation, probabilities of certain events happening (e.g., an ignorant person becoming a zombie), and the probability of citizens moving districts. The simulation models interactions between citizens, including ignorant, alarmed, and zombie citizens, and tracks the progression of the zombie outbreak over time.</p>

  <h2>Features</h2>
  <ul>
    <li>Customizable Simulation: Users can specify the duration of the simulation and probabilities for different events, allowing for flexibility in experimenting with various scenarios.</li>
    <li>Multiple Citizen States: The simulation includes different types of citizens, such as ignorant, alarmed, and zombie citizens, each with unique behaviors and interactions.</li>
    <li>Dynamic District Movement: Citizens can move between districts during the simulation, affecting the spread of the outbreak.</li>
    <li>Interactive Reporting: The simulation provides informative reports at intervals, showing the current state of the outbreak, including the number of zombies, alarmed citizens, and ignorant citizens.</li>
  </ul>

  <h2>Files Included</h2>
  <ul>
    <li>main.cpp: Contains the main function to initiate and run the simulation.</li>
    <li>citizen.h: Header file defining the base class Citizen and its subclasses, representing different types of citizens in the simulation.</li>
    <li>zombie.h: Header file defining the Zombie class, representing zombie citizens.</li>
    <li>alarmed.h: Header file defining the Alarmed class, representing alarmed citizens.</li>
    <li>simulator.h: Header file defining the ZombieSim class, which orchestrates the simulation.</li>
    <li>report.h: Header file defining the Report class, responsible for generating informative reports during the simulation.</li>
  </ul>

  <h2>Data Structures Used</h2>
  <ul>
    <li>STL Map: Used to represent the layout of the simulated city, mapping district names to vectors of strings representing adjacent districts.</li>
    <li>Deque: Used to store and manage the list of citizens within each district during the simulation.</li>
  </ul>

  <h2>Technical Details</h2>
  <ul>
    <li>Language: C++</li>
    <li>Development Environment: Developed and tested using a C++ compiler on various platforms (e.g., Visual Studio, g++)</li>
    <li>Dependencies: Standard C++ libraries only</li>
    <li>Version Control: The project is hosted on GitHub for version control and collaboration.</li>
    <li>Build System: Compiled using a C++ compiler, with a simple Makefile for convenience.</li>
  </ul>

  <h2>Usage</h2>
  <p>To run the simulation, compile the provided source files using a C++ compiler and execute the resulting executable. Follow the prompts to specify simulation parameters such as duration and probabilities. The simulation will then run, providing reports at intervals to track the progression of the outbreak.</p>

  <h2>Acknowledgments</h2>
  <p>This project was inspired by discussions on the cplusplus.com forum and developed as part of the CS-273-2 course.</p>
</body>
</html>
