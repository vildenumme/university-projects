## ⚔️ Equipment Shop — JavaScript basics

A short revision project demonstrating core JavaScript concepts such as variables, objects, functions, DOM manipulation, events, conditions, and simple UI state handling.

![giphy (5)](https://github.com/user-attachments/assets/e2ef6262-b45f-492f-a47c-409d89f19ba3)

### 📘 What this project covers
- **Variables & objects:** `playerInfo`, `shopKeeperInfo`, `swordInfo`, `ShieldInfo`
- **DOM manipulation:** `document.getElementById`, updating `innerHTML` and `style`
- **Functions:** `initGUI`, `buySword`, `buyShield`
- **Conditions (if/else):** checking if the player has enough gold
- **Events:** `onclick` for buttons
- **Template literals:** using backticks (`` `...` ``) to dynamically add images to the output div

### 🗂️ Folder structure
```
project-root/
├─ index.html
├─ css/
│  └─ game-shop.css
└─ images/
   ├─ gold_coin.png
   ├─ shop-owner.png
   ├─ shield_old.png
   └─ sword_1.png
````

### 🚀 How to run
1. Make sure your files follow the structure above.  
2. Open `index.html` in your browser (double-click it or use **Live Server** in VS Code).

### 💡 Suggestions for improvement  
- **UI feedback:** disable buy buttons when the player doesn’t have enough gold.  
- **Refactoring:** move price and quantity updates into helper functions.  
- **Visual feedback:** show a short “toast” or message that fades away after a few seconds.  
- **Inventory system:** add `stock` values and prevent purchases when stock = 0.

