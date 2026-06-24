# AuraSync AR 

![AuraSync AR](https://img.shields.io/badge/Status-Active-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

A next-generation, browser-based Augmented Reality hand tracking experience. 
**AuraSync** utilizes Google's MediaPipe framework combined with raw HTML5 Canvas physics engines to create a highly responsive, cyber-aesthetic, interactive audio-visual environment.
## 🌟 Features

- **Real-time Skeleton Tracking**: Accurately tracks up to two hands simultaneously at 60FPS.
- **Dynamic Themes**: Multiple visual modes including `Prism`, `Neon`, `Magma`, `Abyss`, and `Cosmic`.
- **Procedural Physics Engine**: Fluid trailing motion blur, lightning sparks, shockwaves, and particle generations upon interactions.
- **Reactive Audio Design**: A built-in web audio engine generates dynamic hums based on hand distances and "zaps" upon pinch gestures.
- **Matrix Background Overlay**: Rain effect that speeds up relative to your hand movements.

## 🚀 Quick Start

Since this is a vanilla JS project, you don't need any complex build tools.

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/aurasync-ar.git
   cd aurasync-ar
   ```

2. **Serve locally**
   Use any local web server (e.g. VSCode Live Server, Python HTTP server, or Node.js `serve`):
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve .
   ```

3. **Open in Browser**
   Navigate to `http://localhost:8000`. Grant camera permissions, and enjoy!

## 🛠 Tech Stack

- **HTML5 Canvas**: Native rendering, blend modes, gradients.
- **MediaPipe Hands**: Core ML inference.
- **Web Audio API**: Real-time sound synthesis.
- **Vanilla JavaScript**: Zero heavy framework overhead.

## 🎮 Controls

- **Pinch**: Generates a shockwave and triggers a zap sound.
- **Move Fast**: Speeds up the background Matrix rain and creates intense motion trails.
- **Two Hands**: Connects fingertips with dynamic gradient lines and draws a rotating mandala in the center. Get index fingers close to modulate the audio pitch!

---
*Created with ❤️ by the open source community.*
