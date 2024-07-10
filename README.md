# AI Learns to Drive

This project demonstrates the use of NeuroEvolution of Augmenting Topologies (NEAT) to teach an AI agent to drive a car in a simulated environment using Pygame.

![Demo](demo.gif)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we use NEAT, a genetic algorithm for evolving neural networks, to control a car that learns to navigate a track. The car's objective is to drive as far as possible without colliding with the walls.

## Features

- NEAT algorithm for evolving neural networks
- Pygame for rendering the simulation
- Real-time visualization of the learning process
- Adjustable configurations for NEAT

## Installation

To get started with the project, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/ai-learns-to-drive.git
    cd ai-learns-to-drive
    ```

2. **Set up a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Ensure you have the required images:**
    - Place the car image (`police.png`) and the map image (`map6.png`) in the project directory.

## Usage

To run the simulation, use the following command:

```bash
python main.py
