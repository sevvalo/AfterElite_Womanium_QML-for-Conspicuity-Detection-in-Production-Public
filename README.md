## Team Information:
Team Member 1:

* Full Name: Ahmet Alperen TEKİN
* Womanium Program Enrollment ID: WQ24-nMbUmOCjHyDbRAK

Team Member 2:

* Full Name: Şevval ÖZDEMİR
* Womanium Program Enrollment ID: WQ24-jEy2lgI4HZ4PiG8:
## Project Description: Quantum Machine Learning for Conspicuity Detection in Production

This project is focused on enhancing conspicuity detection in production environments, aiming to identify improvement opportunities in work processes. By analyzing process data, such as images or time series, the project seeks to uncover deviations and weak points in production that can be optimized. Traditional methods for analyzing such data are time-consuming, so this project explores the potential of hybrid quantum computing to accelerate this process.

The main goal is to implement hybrid quantum algorithms and benchmark them against classical approaches, including machine learning and statistical methods. The parcipants are planned to familiarize themselves with the PennyLane framework and its integration with JAX and Quantum Neural Networks (QNNs). The final objective is to implement these prototypes and present the results using standard metrics and visualizations.

## Project Solution

This project explores the application of quantum machine learning techniques, specifically quantum variational classifiers and quantum convolutional neural networks, to the problem of conspicuity detection in production. The project utilizes PennyLane, a quantum machine learning library, and TensorFlow for classical machine learning tasks.

In our solution, after completing the required PennyLane Codebooks, we continued with Task 2. In this task, quantum variational classifier is implemented. 
The process includes:

    Device Setup: Using the default.qubit device in PennyLane.
    Quantum Circuit Design: The circuit consists of a series of rotation gates applied to qubits, followed by CNOT gates for entanglement.
    State Preparation: Inputs are encoded into the quantum circuit using basis states.
    Training: The classifier is trained using the NesterovMomentumOptimizer over 100 epochs. The performance is evaluated using accuracy and mean square error loss metrics.
    Evaluation: After training, the model is tested on a validation dataset, showing promising results in classifying parity data.


The third task explores quantum convolutional neural networks (QCNN) through a Quanvolutional Neural Network model:

    Data Preparation: The MNIST dataset is normalized and downsized for computational feasibility.
    Quantum Circuit Design: A quantum circuit encodes the input images and applies random layers to process the data.
    Quanvolutional Layer: This layer applies quantum operations in a sliding window manner over the input images, effectively simulating the function of classical convolutional layers.
    Integration with Classical Neural Networks: The outputs from the quanvolutional layer are fed into a classical neural network for final classification.

Outcomes and Conclusion

The project demonstrates the potential of quantum machine learning in enhancing conspicuity detection models in production environments. The quantum variational classifier and the Quanvolutional Neural Network both exhibit promising results, indicating that quantum machine learning could offer advantages in tasks requiring high precision and novel data processing techniques. However, further exploration is needed to fully understand the scalability and practical implementation of these quantum models in real-world production systems.
