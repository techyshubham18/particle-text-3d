# 🌌 Particle to 3D Text Animation

An interactive 3D particle network that dynamically morphs into custom text using **Three.js** and **GSAP**. Type any word, and watch thousands of particles assemble to form your text in a smooth, fluid animation.

![Project Preview](https://techyshubham18.github.io/particle-text-3d/)
---

## ✨ Features

*   **Dynamic Text Morphing:** Enter any text (up to 20 characters) and watch particles morph into shape.
*   **Fluid Physics:** Powered by `Three.js` for high-performance 3D rendering and vertex math.
*   **Smooth Transitions:** Uses `GSAP` (GreenSock Animation Platform) for organic particle easing and movement.
*   **Auto-Reset:** Automatically morphs back into a rotating cosmic sphere after a short delay.
*   **Fully Responsive:** Perfectly adapts to any screen size or mobile viewport.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3 (Custom properties & modern layout)
*   **3D Graphics:** [Three.js (r128)](https://threejs.org/)
*   **Animations:** [GSAP (v3.7.1)](https://greensock.com/gsap/)
*   **Fonts:** Inter (via Google Fonts)

---

## 📁 Folder Structure

```text
particle-text-3d/
│
├── .vscode/
│   └── settings.json       # VS Code Live Server configurations
│
├── index.html              # Core layout and external scripts
├── script.js               # Three.js scene, particles, and morphing logic
├── style.css               # Modern glassmorphic UI styling
└── README.md               # Documentation
