# 🦾 Prosthetic Hand Gesture Controller

A real-time hand tracking simulation that demonstrates the core principles behind modern neuroprosthetics and brain-computer interfaces. Track your hand movements via webcam and watch them mirrored on a robotic prosthetic visualization — no hardware required.

🔗 **[Live Demo](https://prosthetic-hand-controller.vercel.app)**

![Demo Screenshot](demo.png)

## ✨ Features

- **Real-time Hand Tracking** — MediaPipe Hands for accurate 21-point landmark detection
- **Prosthetic Visualization** — Metallic robotic hand with glowing LED-style joints
- **Skeleton Mode** — Toggle to see raw landmark connections
- **Gesture Recognition** — Detects 6 gestures:
  - ✊ Fist
  - 🖐️ Open Palm
  - 👆 Pointing
  - ✌️ Peace
  - 👍 Thumbs Up
  - 🤏 Pinch
- **Left & Right Hand Support** — Works with both hands
- **Mirrored Display** — Natural interaction like a mirror
- **Zero Setup** — Runs entirely in the browser

## 🧠 How It Works

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Webcam    │ →   │  MediaPipe  │ →   │   Canvas    │
│   Input     │     │  Hand Track │     │  Rendering  │
└─────────────┘     └─────────────┘     └─────────────┘
                           ↓
                    21 hand landmarks
                    (x, y, z coordinates)
                           ↓
                    Gesture Detection
                           ↓
                    Visual Feedback
```

This project demonstrates key concepts used in real prosthetic systems:

| Real Prosthetics | This Simulation |
|------------------|-----------------|
| EMG sensors read muscle signals | Camera captures hand movements |
| Signal processing algorithms | MediaPipe ML model |
| Motor controllers | Canvas rendering |
| Servo motors | Visual prosthetic hand |

## 🛠️ Tech Stack

- **MediaPipe Hands** — Hand landmark detection
- **Canvas API** — Real-time rendering
- **Tailwind CSS** — Styling
- **Vanilla JavaScript** — No frameworks needed

## 🚀 Quick Start

### Option 1: Use Live Demo
Visit **[prosthetic-hand-controller.vercel.app](https://prosthetic-hand-controller.vercel.app)**

### Option 2: Run Locally
1. Download `index.html`
2. Open in Chrome or Edge
3. Allow camera access
4. Show your hand!

## 📁 Project Structure

```
prosthetic-hand-controller/
├── index.html    ← Single file application
└── README.md     ← Documentation
```

## 🎓 Educational Value

This project is useful for:

- **Biomedical Engineering Students** — Understanding human-machine interfaces
- **Rehabilitation Research** — Demonstrating prosthetic concepts
- **Patient Education** — Showing how modern prosthetics work
- **STEM Outreach** — Engaging demonstrations

## 🔮 Future Enhancements

- [ ] 3D WebGL hand model with Three.js
- [ ] More gesture types (grip patterns)
- [ ] Grip strength visualization
- [ ] Two-hand tracking
- [ ] EMG sensor integration (Arduino)
- [ ] VR/AR compatibility

## 📚 References

- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
- [Hand Landmark Model Paper](https://arxiv.org/abs/2006.10214)
- [Prosthetic Control Systems](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6068572/)

## 👨‍💻 Author

**Mohammad Khalaf**  
Biomedical Engineering Student | Işık University

- 💼 [LinkedIn](https://www.linkedin.com/in/mohammad-khalaf-b80273261)
- 🐙 [GitHub](https://github.com/mohammadkhalaf)

---

*Built as part of my biomedical engineering portfolio — demonstrating the intersection of computer vision, AI, and healthcare technology.*
