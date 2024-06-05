# Node-Red application for IoT

This repository contains a Node-RED flow for an IoT application and a set of slides describing a potential use case for the flow. The aim is to demonstrate how Node-RED can be used to implement IoT solutions effectively.

## Table of Contents

- [Files](#files)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Files

### 1. `IoT_flow.json`
This file contains a Node-RED flow in JSON format. It includes nodes for connecting to IoT devices, processing data, and outputting results. This flow can be imported directly into a Node-RED instance.

### 2. `IoT_Use_Case_Slides.pdf`
This PDF file contains a set of slides describing a specific use case for the Node-RED IoT flow. The slides detail the problem, the solution provided by the IoT flow, and the benefits of implementing this solution.

## Prerequisites

To use the files in this repository, you will need the following:

- **Node-RED**: A flow-based development tool for visual programming suitable for wiring together hardware devices, APIs, and online services.
- **PDF viewer**: Any application capable of opening PDF files to view the slides.

## Installation

### Node-RED

1. Install Node-RED by following the instructions on the [Node-RED website](https://nodered.org/docs/getting-started/).

2. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/iot-flow-use-case.git
    cd iot-flow-use-case
    ```

3. Open your Node-RED instance in a web browser:
    ```
    http://localhost:1880
    ```

4. Import the `IoT_flow.json` file into Node-RED:
    - Click on the menu (top right corner) -> Import -> Clipboard.
    - Open the `IoT_flow.json` file in a text editor, copy its contents, and paste them into the Node-RED import dialog.
    - Click 'Import'.

### Viewing the Slides

1. Open the `IoT_Use_Case_Slides.pdf` file using any PDF viewer.

## Usage

### Running the Node-RED Flow

1. After importing the flow, deploy it by clicking the "Deploy" button in Node-RED.
2. Ensure your IoT devices or simulators are connected and configured correctly.
3. Monitor the flow to see data processing and output in real-time.

### Reviewing the Use Case

1. Open `IoT_Use_Case_Slides.pdf` to understand the context and application of the Node-RED flow.
2. Use the slides to present the use case to stakeholders or for educational purposes.

## Contributing
- Sara Huang
- Ziad Elharairi
- Massimiliano Cristina

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue in the repository.


