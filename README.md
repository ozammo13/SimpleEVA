# SimpleEVA
A simple libary to use the EVA robot arm in python. This libary simplifies the use of IK and allows for easy control of the robot arm.

## Installation
To install the libary, run the following command:
```bash
pip install simpleeva
```

## Usage
To use the libary, you must first import it:
```python
import simpleeva
```
Then, you must create an instance of the robot arm:
```python
eva = simpleeva.EvaController.RobotArm()
```
