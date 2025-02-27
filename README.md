# 🚀 Jetbot

Jetbot is a lightweight, open-source robotics project based on NVIDIA Jetson for AI-powered robotic applications such as object following, collision avoidance, and road following.

## 📂 Project Structure

This repository consists of multiple modules to control and navigate the Jetbot:

- **basic_motion/** - Contains scripts for basic movement and motor control.
- **collision_avoidance/** - Implements AI-based collision avoidance using a camera.
- **object_following/** - Enables object detection and following using deep learning models.
- **road_following/** - Implements lane and road following using computer vision techniques.
- **teleoperation/** - Allows remote control of the Jetbot using external devices.

## 🛠 Installation & Setup

To set up and run Jetbot, follow these steps:

### Prerequisites
- NVIDIA Jetson Nano with JetPack installed
- Python 3.x
- Required libraries: `torch`, `torchvision`, `numpy`, `opencv-python`

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/poommin2543/Jetbot.git
   cd Jetbot
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the desired module:
   ```bash
   python collision_avoidance/main.py
   ```

## 🎯 Features
- AI-based **Object Detection** and **Object Following**
- **Lane Detection** for autonomous road following
- **Collision Avoidance** using deep learning models
- **Remote Teleoperation** for manual control
- Compatible with NVIDIA Jetson Nano

## 📖 Usage Guide
1. **Basic Motion**
   - Run `python basic_motion/move.py` to test motor functions.
2. **Collision Avoidance**
   - Run `python collision_avoidance/main.py` to activate obstacle detection.
3. **Object Following**
   - Run `python object_following/main.py` to detect and follow objects.
4. **Road Following**
   - Run `python road_following/main.py` for lane tracking.
5. **Teleoperation**
   - Use external controllers to manually drive the robot.

## 🤝 Contributing
Feel free to contribute to this project by submitting pull requests. Ensure that your code follows proper documentation and best practices.

## 📜 License
This project is open-source and available under the MIT License.

## 📞 Contact
For any questions, feel free to reach out via GitHub Issues.

GitHub: [poommin2543](https://github.com/poommin2543)

Happy Coding! 🚀
