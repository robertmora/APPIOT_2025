# APPIOT 2025 Exploring MQTT

This repository contains two Python scripts demonstrating the basic functionalities of MQTT protocol: a publisher (`publisher.py`) and a subscriber (`subscriber.py`). These scripts are designed as simple examples to help understand how MQTT communication works in the context of IoT applications.

## Prerequisites

Before running these scripts, ensure you have the correct prerequisites installed as per Lab instructions.

Additionally, you'll need access to an MQTT broker. For testing purposes, you can install Mosquitto, a lightweight open-source MQTT broker, on your local machine:

```bash
sudo apt update -y && sudo apt install mosquitto
```

## Getting Started

To get started with these examples, first clone this repository to your local machine. For instance, to clone it to the lab virtual machine, you could use:

```bash
cd /home/networkedss/Desktop/appiot_lab2
git clone https://github.com/robertmora/APPIOT2024_Lab2
```

Navigate to the cloned directory:

```bash
cd APPIOT2024_Lab2
```

### Running the Publisher

To run the publisher script, which sends a message to a specified topic, use:

```bash
python publisher.py
```

### Running the Subscriber

To start the subscriber script, which listens for messages on a specified topic, execute:

```bash
python subscriber.py
```

## About the Scripts

- `publisher.py`: Sends a predefined message to a specific topic.
- `subscriber.py`: Listens for messages on a specific topic and prints any messages it receives to the console.

These scripts are intended as educational tools to introduce the basics of MQTT protocol and should be modified or extended according to your specific learning or development goals.

