# Guess The Word Game

An interactive web-based word guessing game with modern animations, sound effects, and gamification elements.

## 🚀 Live Demo

👉 [https://vasylpryimakdev.github.io/word-guessing-game/](https://vasylpryimakdev.github.io/word-guessing-game/)

## 🎮 Game Features

- **Word Guessing**: Guess 5-letter words letter by letter
- **Lives System**: Start with 8 lives (hearts) that decrease with wrong guesses
- **Points & Coins**: Earn 10 coins for each correct letter guess
- **Shop System**: Buy additional lives for 25 coins
- **Sound Effects**: Audio feedback for correct/wrong guesses, wins, and losses
- **Modern UI**: Clean, responsive design with smooth animations
- **Visual Feedback**: Hearts for lives, coin counter, and animated transitions

## 🎯 How to Play

1. **Start**: The game begins with a hidden 5-letter word
2. **Guess Letters**: Click on letter buttons to make your guess
3. **Earn Points**: Get 10 coins for each correct letter
4. **Manage Lives**: Wrong guesses cost you a life (heart)
5. **Buy Lives**: Use coins to purchase extra lives when running low
6. **Win**: Guess the complete word before running out of lives
7. **New Game**: Start over after winning or losing

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS variables and animations
- **Vanilla JavaScript**: Game logic and interactivity
- **Web Audio API**: Sound effect management
- **Google Fonts**: Salsa font for playful typography

## 📁 Project Structure

```
words-game/
├── index.html          # Main game HTML
├── script.js           # Game logic and JavaScript
├── styles.css          # Styling and animations
├── assets/             # Game assets
│   ├── *.mp3          # Sound effects
│   └── *.svg          # Icons (hearts, coins)
└── README.md           # This file
```

## 🚀 Getting Started

1. Clone the repository

```bash
git clone https://github.com/vasylpryimakdev/word-guessing-game.git
cd word-guessing-game
```

2. **Open `index.html`** in your web browser
3. **Start Playing** - No additional setup required!

### Local Development

For local development with live reload:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using Live Server in VS Code
# Right-click index.html and select "Open with Live Server"
```

## 🎮 Game Controls

- **Mouse/Touch**: Click letter buttons to make guesses
- **Buy Button**: Purchase additional lives (when enabled)
- **New Game Button**: Restart after game over

## 🏆 Game Mechanics

- **Word Length**: 5 letters
- **Starting Lives**: 8 hearts
- **Life Cost**: 25 coins per additional life
- **Point Reward**: 10 coins per correct letter
- **Letter Selection**: Each letter can only be guessed once per game

## 🎨 Customization

### Changing Words
Edit the `script.js` file to modify the word list or add new words.

### Styling
Modify `styles.css` to change colors, fonts, and animations. The game uses CSS variables for easy theming:

```css
:root {
  --bg: #251f18;      /* Background color */
  --beige: #af9876;    /* Accent color */
  --orange: #ff9800;   /* Highlight color */
}
```

### Sound Effects
Replace MP3 files in the `assets/` folder to customize audio feedback.

## 🌐 Browser Compatibility

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

**Enjoy playing Guess The Word! 🎉**
