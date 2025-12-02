# ⌨️ Typing Speed Game (Streamlit)

An interactive typing speed game built with **Streamlit** that measures your typing **speed (WPM)** and **accuracy** across multiple difficulty levels.

The app:
- Shows a random sentence based on difficulty (Easy / Medium / Hard)
- Tracks how long you take to type it
- Calculates your **Words Per Minute (WPM)**
- Compares typed text with the original and highlights **correct** and **incorrect** words
- Stores and displays a **high score leaderboard** using a local text file :contentReference[oaicite:0]{index=0}

## 🚀 Features

- 🎚 **Difficulty Levels**: Easy, Medium, Hard (different sentence pools)
- ⏱ **Live Timing**: Measures time taken from when you start typing
- 📊 **Performance Metrics**:
  - WPM (Words Per Minute)
  - Total words typed
  - Time taken (seconds)
  - Accuracy (% based on word-by-word comparison)
- ✅ **Visual Feedback**:
  - Correct words highlighted in green
  - Incorrect/missing words highlighted in red
- 🏆 **High Score System**:
  - Scores saved in `high_scores.txt`
  - Top scores sorted by WPM and accuracy
- 👤 **User Name Support**:
  - Enter your name before starting
  - Defaults to `Anonymous` if left empty
