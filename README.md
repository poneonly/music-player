# 🎵 Music Player Web App

A simple, basic music player website built with **HTML**, **CSS**, and **JavaScript**. This project was created as a way to practice JavaScript by implementing core music player functionalities like play/pause, skip, repeat, and random playback.

---

## 🌐 Live Demo

🔗 **Try it now**: [https://poneonly.github.io/music-player/](https://poneonly.github.io/music-player/)

---

## 🚀 Features

* ✅ Play and pause songs
* ⏭️ Skip to next / previous songs
* 🔁 Toggle repeat and random playback
* 💼 Animated rotating CD thumbnail
* 📂 Playlist with active song highlighting
* 📉 Interactive progress bar with seek functionality
* 📦 LocalStorage support for saving settings (repeat/random)

---

## 📸 Screenshot

![Screenshot of Music Player](./assets/images/congdien1.png)

---

## 🛠️ Built With

* HTML5
* CSS3 (Flexbox, Animations)
* Vanilla JavaScript (DOM, Events, Audio API)
* [Font Awesome](https://fontawesome.com/) - for UI icons
* [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins)

---

## 📂 Project Structure

```
music-player/
│
├── assets/
│   ├── images/         # CD thumbnails
│   └── songs/          # MP3 files
│
├── index.html          # Main HTML file
├── index.css           # Styling
└── script.js           # JavaScript logic (inside index.html or separate)
```

---

## 📦 Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/music-player.git
cd music-player
```

2. Open the `index.html` file in your browser.

> This project runs completely in the browser — no backend or build step required.

---

## 🧐 How It Works

* Songs are preloaded from a JavaScript array.
* Playback state (e.g., random, repeat) is saved using `localStorage`.
* The CD image rotates while music plays and stops when paused.
* Users can scroll and select songs from the playlist.
* The current song is auto-highlighted and scrolled into view.
* Clicking a song loads and plays it immediately.
* Repeat and shuffle buttons reflect the saved state across page refreshes.
* Scroll event dynamically resizes the CD image for UI effect.

---

## 🤝 Contributing

Pull requests are welcome!
If you have suggestions for improvements or new features, feel free to fork this project.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Aiden Tran**
IT Major — Network Engineering

🔗 GitHub: [poneonly](https://github.com/poneonly)

---
