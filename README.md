# 🖐️ Advance Hand Tracking AR

A browser-based Augmented Reality experience that uses your webcam to detect your hand in real-time, track all 21 finger landmarks, and render glowing connection lines between them — no installation required.

---

## ✨ Features

- **Zero Setup** — runs entirely in the browser, no installs or dependencies
- **Real-Time Hand Tracking** — detects and maps all 21 hand landmarks instantly
- **Dynamic Line Connections** — draws unique glowing lines connecting every finger joint and tip
- **AR Overlay** — renders directly on top of your live camera feed
- **Lightweight** — single `index.html` file, powered by MediaPipe

---

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/thechiranjeevvyas/Advance-Hand-tracking-AR.git
   cd Advance-Hand-tracking-AR
   ```

2. **Open in browser**
   Just open `index.html` in any modern browser (Chrome recommended):
   ```bash
   open index.html
   # or double-click the file
   ```

3. **Allow camera access** when prompted

4. **Hold up your hand** in front of the camera and watch the AR lines appear ✋

---

## 🛠️ How It Works

| Step | Description |
|------|-------------|
| 📷 Camera Feed | Captures live video via the browser's `getUserMedia` API |
| 🧠 Hand Detection | Uses **MediaPipe Hands** to detect and map 21 landmarks per hand |
| 🔗 Line Rendering | Draws unique connection lines between all finger joints on a `<canvas>` overlay |
| 🎨 AR Effect | Canvas is overlaid on the video feed, creating a real-time AR visual |

---

## 📋 Requirements

- A modern browser with WebRTC support (Chrome, Edge, Firefox)
- A working webcam
- That's it.

---

## 📁 Project Structure

```
Advance-Hand-tracking-AR/
└── index.html   # Everything — camera, tracking, and rendering in one file
```

---

## 🤝 Contributing

Pull requests are welcome! Feel free to open an issue for bugs, feature requests, or improvements.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Credits

Made with ❤️ by **[@thechiranjeevvyas](https://github.com/thechiranjeevvyas)**
