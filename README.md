# AeroCare: LSTM-driven Predictive Maintenance Solution for Aircraft Engines

![AeroCare Logo](https://repository-images.githubusercontent.com/367575779/6244d500-b563-11eb-81bf-4152336a0af8)

---

## Overview

AeroCare is a predictive maintenance solution designed specifically for monitoring and maintaining aircraft engines using LSTM (Long Short-Term Memory) neural networks. This project aims to enhance the safety, reliability, and efficiency of aircraft operations by predicting engine failures before they occur, thereby reducing downtime and maintenance costs.

---

## Key Features

- LSTM-based predictive modeling for engine health monitoring
- Real-time data ingestion and processing
- Anomaly detection and early fault prediction
- Web dashboard for visualization and analysis
- Scalable architecture for handling large volumes of data
- Integration with existing aircraft maintenance systems

---

## Software Environment
* Python 3.6
* numpy 1.13.3
* scipy 0.19.1
* matplotlib 2.0.2
* spyder 3.2.3
* scikit-learn 0.19.0
* h5py 2.7.0 
* Pillow 4.2.1 
* pandas 0.20.3
* TensorFlow 1.3.0
* [Keras 2.1.1](https://keras.io)

---

## Problem Description
In this scenario, I've constructed an LSTM (Long Short-Term Memory) network to predict the remaining useful life or time to failure of aircraft engines <a href="https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan">[3]</a>. This prediction is based on the context outlined in references <a href="https://github.com/Azure/lstms_for_predictive_maintenance/blob/master/Deep%20Learning%20Basics%20for%20Predictive%20Maintenance.ipynb">[1]</a> and <a href="https://gallery.azure.ai/Experiment/Predictive-Maintenance-Step-2A-of-3-train-and-evaluate-regression-models-2">[2]</a>.
The system utilizes simulated aircraft sensor data to forecast the future failure of aircraft engines, enabling proactive maintenance planning.
Can we anticipate the failure of an in-service aircraft engine by analyzing its operational data and past failure events? 
This involves two main inquiries, approached with distinct machine learning models:

	* Regression Analysis: Estimating the remaining operational cycles before an engine failure occurs.
	* Binary Classification: Determining if an engine is likely to fail within a specified number of upcoming cycles.

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/aerocare.gi
    ```
---

## Usage

1. Access the AeroCare dashboard through your web browser.
2. Upload historical engine data or connect to real-time data sources.
3. Train the LSTM model using the provided data.
4. Monitor engine health status and receive predictive maintenance alerts.
5. Perform necessary maintenance tasks based on the recommendations provided by AeroCare.

---

## References

- [1] Deep Learning for Predictive Maintenance https://github.com/Azure/lstms_for_predictive_maintenance/blob/master/Deep%20Learning%20Basics%20for%20Predictive%20Maintenance.ipynb
- [2] Predictive Maintenance: Step 2A of 3, train and evaluate regression models https://gallery.azure.ai/Experiment/Predictive-Maintenance-Step-2A-of-3-train-and-evaluate-regression-models-2
- [3] A. Saxena and K. Goebel (2008). "Turbofan Engine Degradation Simulation Data Set", NASA Ames Prognostics Data Repository (https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan), NASA Ames Research Center, Moffett Field, CA 
- [4] Understanding LSTM Networks http://colah.github.io/posts/2015-08-Understanding-LSTMs/

---

## Contributing

Contributions to AeroCare are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on GitHub.

---

## Acknowledgements

We would like to thank the open-source community for their valuable contributions and the support received during the development of AeroCare.
