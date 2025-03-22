# Boat Race Simulation

## Overview
The Boat Race Simulation is a fun and interactive web-based project that allows users to simulate a boat race with customizable teams. The simulation runs for 5 seconds, after which it displays the finishing order of the boats, with the winner being chosen randomly.

## Project Structure
```
boat-race-simulation
├── index.html          # Main HTML document for the simulation
├── css
│   └── styles.css     # Styles for the simulation
├── js
│   ├── main.js        # Entry point for JavaScript code
│   ├── simulation.js   # Logic for running the boat race simulation
│   ├── boat.js        # Defines the Boat class
│   ├── team.js        # Defines the Team class
│   ├── renderer.js    # Handles rendering of the race
│   └── results.js     # Manages display of race results
├── assets
│   └── sounds
│       └── finish.mp3 # Audio asset for race finish
└── README.md          # Documentation for the project
```

## Features
- **Customizable Teams**: The simulation supports up to 8 teams, allowing users to customize team names.
- **2D Side View**: The race is displayed in a 2D side view, providing a clear visual representation of the boats.
- **Race Duration**: The race lasts for 5 seconds, creating an exciting and fast-paced experience.
- **Random Winner Selection**: The winner is determined randomly, adding an element of surprise to each race.
- **Results Display**: After the race, the finishing order is displayed, highlighting the winning team.

## Setup Instructions
1. Clone the repository to your local machine.
2. Open `index.html` in a web browser to start the simulation.
3. Customize the number of teams by modifying the relevant section in `main.js`.

## How to Customize Teams
To change the number of teams in the simulation, locate the team initialization section in `js/main.js` and adjust the number of teams as desired. You can also modify the team names to personalize your race experience.

## License
This project is open-source and available for anyone to use and modify. Enjoy racing!