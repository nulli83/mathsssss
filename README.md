inspired by https://www.linkedin.com/posts/saadhana-k-449743326_built-a-virtual-calculator-powered-by-activity-7358051018296729603-popl?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFCm7JAB3_ZiYgdDIay-UY4ei98-G6O9ap8

# Gesture-Controlled Contactless Calculator

A cutting-edge project that lets you operate a fully functional calculator using only hand gestures captured by your webcam — no physical touch needed. Harnessing real-time hand detection powered by a state-of-the-art AI model, this application transforms your hand into a natural, intuitive pointer to interact with the on-screen interface.

## Project Overview

This project was built to explore the future of human-computer interaction by eliminating the need for physical contact. The user controls a virtual calculator by hovering their hand over buttons; holding still over a number or operator triggers a selection — just like a click. This makes it perfect for environments where touchless interaction is crucial, including accessibility solutions, public installations, or hygienic applications.

With a sleek OpenCV-based graphical interface and robust YOLOv8-powered hand recognition, this project combines AI, computer vision, and user interface design into one seamless experience.

## Key Features

* **Real-time webcam feed** with live hand tracking
* **Accurate hand detection** using YOLOv8 (Ultralytics)
* **Hover-based click system** for intuitive input
* **Basic arithmetic operations** implemented in the calculator
* **Clean, minimalist UI** drawn with OpenCV for smooth interaction

## Technologies Used

| Technology           | Purpose                                      |
| -------------------- | -------------------------------------------- |
| Python               | Core programming language                    |
| OpenCV               | Video capture, UI rendering                  |
| YOLOv8 (Ultralytics) | Real-time hand detection AI                  |
| NumPy                | Mathematical operations and image processing |

*Note: Initially, MediaPipe was used for hand tracking but was replaced due to compatibility issues.*

## Getting Started

### Clone the repository

```bash
git clone https://github.com/nulli83/gesture-calculator.git
cd gesture-calculator
```

### Install dependencies

```bash
pip install -r requirements.txt
pip install ultralytics
```

### Run the application

```bash
python main.py
```

## Use Cases

* Touchless public kiosks and info screens
* Accessibility tools for users with mobility challenges
* Hygienic interfaces in healthcare or food services
* Interactive art and tech installations

## Important Notes

* Adequate lighting conditions improve hand detection accuracy
* Simple backgrounds help reduce noise and false detections
* Camera quality and distance to hand affect performance

---

I’m really proud of how this project combines AI, computer vision, and UI to create a futuristic way to interact with machines — no touch needed. It opens up tons of possibilities for next-level interfaces and accessibility, and I’m excited to keep developing it further!
