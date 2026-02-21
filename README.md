# 🚀 Cosmic Number Guesser

A space-themed number guessing game built with pure HTML, CSS, and JavaScript. Guess the hidden number between 1 and 100 before your attempts run out — all set against a fully interactive, animated space background.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🎮 How to Play

1. A random number between **1 and 100** is chosen at the start of each game
2. Enter your guess in the input field and press **Submit** or hit **Enter**
3. The game tells you if your guess is **too high** or **too low**
4. You have **10 attempts** to find the correct number
5. The **Min/Max** display narrows as you guess to help you zero in
6. Press **New Game** at any time to start fresh

---

## ✨ Features

### 🎯 Gameplay
- 10 guesses per round with a live countdown
- Dynamic Min/Max range tracker that updates with every guess
- Full guess history log with numbered attempts
- Win and Game Over states with clear feedback

### 🌌 Interactive Space Background
- **5 animated planets** — Jupiter, Saturn (with rings), Earth, Mars, and Neptune — each with orbiting moons
- **14 rotating asteroids** you can grab and throw across the screen
- **Comet** that streaks across with a glowing tail and resets on loop
- **200 twinkling stars** with randomised phase and speed
- **5 nebula clouds** adding depth and atmosphere
- **Shooting stars** that appear every few seconds
- All space objects are **draggable** with both mouse and touch

### 🔊 Sound System
- Sound effects for: game start, correct guess, wrong guess, and the easter egg
- Volume slider with mute toggle
- Gracefully silent if sound files are missing

### 🥚 Easter Egg
- Click the **ⓘ info button** 6 times to unlock **+5 bonus guesses**

### 📱 Fully Responsive
- Scales cleanly from small phones (320px) up to large desktop monitors
- Touch-optimised inputs and draggable objects
- Uses `100dvh` for correct height on mobile browsers

---

## 📁 File Structure

```
/
├── index.html          # Main game file (everything is self-contained)
└── sounds/
    ├── click.mp3       # Button click sound
    ├── start.mp3       # New game sound
    ├── win.mp3         # Correct guess sound
    ├── wrong.mp3       # Wrong guess sound
    └── cong.mp3        # Easter egg unlock sound
```

---

## 🚀 Getting Started

No build tools or dependencies required. Just clone and open.

```bash
git clone https://github.com/your-username/cosmic-number-guesser.git
cd cosmic-number-guesser
```

Then open `index.html` in any modern browser — that's it.

> **Note:** Sound effects require the `sounds/` folder to be present alongside `index.html`. The game works fine without it, just silently.

---

## 🌐 Deployment

This project is a single HTML file and can be deployed anywhere static files are hosted:

- **Cloudflare Pages** — connect your repo and deploy instantly
- **GitHub Pages** — enable in your repo Settings → Pages
- **Netlify** — drag and drop the folder or connect via Git
- **Vercel** — import the repo and deploy with zero config

---

## 🛠️ Built With

- **HTML5 Canvas** — for the entire animated space background engine
- **CSS3** — animations, gradients, `clamp()` for fluid responsive scaling, `100dvh`
- **Vanilla JavaScript** — two self-contained IIFEs: one for the space engine, one for game logic
- **Google Fonts** — Orbitron & Press Start 2P
- **Font Awesome 6** — volume control icons

---

## 👨‍💻 Developer

Made by **Tanjim Khan**

---

## 📄 License

This project is open source. Feel free to fork, modify, and use it however you like.
