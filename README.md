# 🎯 Wingo Color Prediction Web Tool

This is a simple, offline-capable web-based tool designed to **predict Wingo game colors** based on a 4-digit game sequence input.

The tool displays 20 sequential predictions every 5 seconds, based on a simple logic model. Each result is visualized with animated color circles and user feedback buttons for marking accuracy.

---

## 🔮 Features

- ✅ **Color prediction only**: Green, Green & Purple, Purple, Red & Purple, Red.
- 🔁 **Automatic prediction** every 5 seconds (20 rounds).
- 🧮 Based on user-entered **last 4 digits of a game sequence**.
- 🖱️ **Interactive buttons** to mark Win/Lose on each prediction.
- 🎨 Eye-catching **animated color circles**.
- 🕵️ Simple logic model with modular code.

---

## 📦 How to Use

1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Enter the last 4 digits of your Wingo game sequence.
4. Click **Start Prediction** to begin.
5. Watch predictions appear every 5 seconds.
6. Mark each result as **Win** or **Lose** using the inline buttons.
7. Click **Stop** at any time to halt predictions.

---

## 🧠 Prediction Logic (Simplified)

- Accepts a **4-digit input** from the user.
- Generates a number from `0–9` using a custom formula.
- Converts the result into a **color category**:
  - `Green`: 1, 3, 5, 7, 9  
  - `Red`: 0, 2, 4, 6, 8  
  - `Purple`: 0 or 5  
  - Combinations like **Green & Purple** and **Red & Purple** are derived based on overlapping rules.

---

## 🖼️ UI Snapshot

Each prediction appears like this:

```
Draw #1234: [🟢] Green & Purple  [Win] [Lose]
```

Where the circle color is animated and styled according to the result.

---

## 🚀 Tech Stack

- HTML5 / CSS3
- JavaScript (Vanilla)
- No frameworks required
- Works fully **offline**

---

## 📁 File Structure

```
.
├── index.html        # Main UI
├── style.css         # Styling and animations
├── wingo.js          # Prediction logic
├── README.md         # Project information
```

---

## 📜 License

This project is licensed for educational and experimental use only. No affiliation with the official Wingo platform.

---

## 🤝 Contributing

Feel free to fork this repo and enhance prediction logic, design, or add analytics. Pull requests are welcome.Draw #1234: [🟢] Green & Purple  [Win] [Lose]
