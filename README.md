# Monster Chef Lite 2.0

A fun browser-based cooking game where you serve meals to hungry monsters and discover what foods they love — or hate.

---

## 🎮 About the Game

**Monster Chef Lite 2.0** is a simple interactive browser game where players create dishes for different monsters.

Each monster has:
- Foods they **like**
- Foods they **dislike**

Players:
1. Pick a monster
2. Add ingredients to a plate
3. Serve the dish
4. Watch the monster react
5. Earn or lose points based on the meal

---

## ✨ Features

- Multiple unique monsters
- Different ingredient combinations
- Score tracking system
- Sound effects for reactions
- Interactive plate system
- Beginner-friendly code structure
- Works directly in the browser

---

## 🚀 How to Run the Project

1. Download or clone the repository
2. Open the `index.html` file in your web browser
3. Start playing immediately

No installation or setup required.

---

## 🛠 Dependencies

This project:
- Works in modern browsers like Chrome, Firefox, Edge, and Safari
- Uses only HTML, CSS, and JavaScript
- Requires no external libraries or frameworks

---

## 📂 Project Structure

```plaintext
Monster-Chef-Lite-2.0/
│
├── index.html
├── README.md
└── assets/
```

---

## 🧠 How the Game Works

### Monsters

Each monster contains:
- A name
- Favorite foods
- Foods they dislike
- An image

Example:

```javascript
{
  name: "Bubby",
  likes: ["Apple", "Banana"],
  dislikes: ["Squid"]
}
```

### Ingredients

Players can choose ingredients and place them onto a plate before serving.

### Scoring

- Good meals increase your score
- Bad meals decrease your score
- Scores never go below 0

---

## 💻 Technologies Used

- HTML5
- CSS3
- JavaScript

---

## 📝 Code Highlights

### Dynamic Rendering

The game creates monsters and ingredients dynamically using JavaScript.

```javascript
function renderMonsters() {
  monsterDiv.innerHTML = '';
}
```

### Interactive Plate

Ingredients appear in random positions on the plate for a fun visual effect.

```javascript
const angle = Math.random() * 2 * Math.PI;
```

### Sound Effects

Audio feedback plays when food is served and when monsters react.

---

## 📖 Reflection

AI helped by:
- Adding beginner-friendly comments throughout the code
- Organizing the project into a clean README structure
- Improving readability and explanations

Small edits were made to:
- Keep the README casual and simple
- Make the comments easier for beginners to understand

---

## 👩‍💻 Author

Made by **Naomi**
