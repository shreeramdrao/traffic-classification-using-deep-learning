
# Intelligent SDN Traffic Classification Using Deep Learning

## Overview

This project focuses on generating and classifying Software-Defined Networking (SDN) traffic to differentiate between normal and abnormal packets using deep learning techniques. The project leverages Mininet, RYU (a Python-based SDN controller), TensorFlow, and Deep Neural Networks to build an intelligent system capable of real-time traffic classification. The implementation is done in Jupyter Notebook for interactive development and easy visualization.

## Table of Contents

- [Dataset](#dataset)
- [Models Used](#models-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Dataset

The dataset for this project comprises network traffic data, specifically designed to include both normal and abnormal packets. The traffic data is generated using Mininet, an SDN network emulator, and classified using deep learning models.

## Models Used

The following tools and technologies are utilized in this project:

- **Mininet**: An SDN network emulator used for generating traffic data.
- **RYU SDN Controller**: A Python-based controller managing the network.
- **TensorFlow**: A deep learning framework used to build and train models.
- **Deep Neural Networks (DNNs)**: The architecture used for classifying network traffic.

## Installation

To set up the environment for this project, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/intelligent-sdn-traffic-classification.git
    cd intelligent-sdn-traffic-classification
    ```

2. **Install Dependencies**:
    Make sure you have Python 3.7+ installed. Install the required Python packages:

3. **Install Mininet**:
    Mininet requires additional setup. Follow the installation instructions on the [Mininet website](http://mininet.org/download/).

4. **Install RYU**:
    Install RYU using pip:
    ```bash
    pip install ryu
    ```

5. **Install Jupyter Notebook**:
    If Jupyter Notebook is not already installed, you can install it using:
    ```bash
    pip install notebook
    ```

## Usage

1. **Launch Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

2. **Open the Main Notebook**:
    Open `traffic_classification.ipynb` in the Jupyter Notebook interface. This notebook contains all the necessary code to generate traffic, train the deep learning model, and evaluate the results.

3. **Run the Cells**:
    Execute the cells in the notebook sequentially. The notebook is organized to guide you through the entire process, from data generation to model training and evaluation.

## Results

The notebook includes detailed results, such as accuracy, precision, recall, and confusion matrices, which provide insights into the performance of the deep learning model in classifying SDN traffic.

## Contributing

Contributions are welcome! Feel free to fork this repository, make enhancements, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the developers of Mininet and RYU for providing essential tools for SDN emulation and control.
- Special thanks to the TensorFlow community for their support and resources.

---
