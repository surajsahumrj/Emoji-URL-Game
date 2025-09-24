# 🎮 Emoji URL Game

Live Demo 👉 [emoji-url-game.netlify.app](https://emoji-url-game.netlify.app/)

A fun little experiment where you **play a space-shooter game directly inside the browser URL bar**. Inspired by [Matthew Rayfield’s blog post](https://matthewrayfield.com/articles/animating-urls-with-javascript-and-emojis/), this project reimagines the classic **Chicken Invaders** with emojis, entirely animated via the `location.hash`.

---

## 🚀 Features

* 🎯 **Shoot chickens & eggs** – fire lasers at 🐓 and 🥚 to score points.
* 🛸 **Don’t shoot the UFO** – protect the spaceship to keep the game alive.
* 🏆 **Live Score & High Score tracking**.
* 📱 **Responsive controls** –

  * **Desktop:** Press ➡️ arrow key to shoot.
  * **Mobile:** Tap the screen to shoot.
* ✨ **Emoji-based animation in the URL bar** (no canvas, no DOM-heavy graphics).
* 🎨 Sleek, modern UI with dark theme and subtle styling.

---

## 🕹️ How to Play

1. Open the [live game](https://emoji-url-game.netlify.app/).
2. Look at the **URL bar** – that’s where the game happens!
3. **Shoot (➡️ / tap)** to destroy chickens 🐓 and eggs 🥚.
4. **Avoid hitting the UFO 🛸** or it’s game over.
5. Keep scoring and beat your high score!

---

## 📂 Project Structure

This game is fully contained in a single **HTML file**:

* **HTML** → Game layout, instructions, GitHub ribbon.
* **CSS** → Dark theme, responsive styling, mobile-friendly.
* **JavaScript** →

  * Game logic (spawning, collisions, score handling).
  * URL bar animation using `location.hash`.
  * Input handling (keyboard & touch).

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3** (responsive design)
* **Vanilla JavaScript** (no libraries/frameworks)

---

## 📸 Screenshots

### Desktop View

![Game Screenshot](https://i.ibb.co/b3W1Rmv/emoji-url-game.png)

*(Shows the URL bar gameplay in action)*

---

## 🙏 Inspiration

This project is inspired by [Matthew Rayfield’s brilliant article](https://matthewrayfield.com/articles/animating-urls-with-javascript-and-emojis/) on animating URLs with JavaScript and emojis.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a PR.

---

## 📜 License

This project is open-source under the **MIT License**.

Would you like me to also **add a section for "Future Improvements"** (like power-ups, sound effects, difficulty levels), so contributors can see where the project could evolve?
