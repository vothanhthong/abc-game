# NoiTu Game - iOS Development Project

## Overview

NoiTu Game is an engaging and interactive word association game designed to challenge and enhance players' linguistic and cognitive skills. Developed as part of the COSC2659 iOS Development course at RMIT University Vietnam, this app combines fun gameplay with cognitive development benefits, providing players with an educational and entertaining experience.

## Features

### Main Features
1. **Menu View (Welcome View)**
   - Displays a welcome screen with buttons for various actions like playing, viewing instructions, adjusting settings, and checking the leaderboard.
   - Features support for different locales, dark mode, and accent color management.

2. **Leaderboard View**
   - Displays a scrollable list of players, showing their positions, scores, achievements, total wins, and plays.
   - Allows players to track their progress and compare it with others.

3. **Game View**
   - Includes interactive gameplay where players register usernames, select levels, and input words to score points.
   - Real-time feedback with correct answers highlighted in green and a "Game Over" option.

4. **Game Settings View**
   - Features options to toggle between dark/light modes, switch languages (English/Vietnamese), and set difficulty levels (Easy, Medium, Hard).

5. **How To Play View**
   - A comprehensive guide split into four tabs:
     - **Rule:** Explains game objectives and mechanics.
     - **Username:** Instructions for registering a username.
     - **Level:** Guidelines for selecting game levels.
     - **Play:** Step-by-step instructions for gameplay with visual aids.

### Advanced Features
1. **Game Progression and Levels**
   - Players can unlock levels progressively based on performance.
   - Level-specific challenges with corresponding target scores.

2. **Theme Toggle**
   - Light and dark themes customizable through SwiftUI's `environment` modifier.

3. **Save and Resume**
   - Players can save their progress and resume gameplay seamlessly.
   - Utilizes `UserDefaults` for saving game states and JSON encoding/decoding for player data.

4. **Multiple Language Support**
   - Supports English and Vietnamese with localization via `Localizable.strings` files.
   - Dynamic UI updates based on the selected language.

5. **Sound and Enhanced UI**
   - Immersive sound effects and user-friendly UI designed for both light and dark modes.

## Gameplay Tips
- Think creatively and quickly to maximize points.
- Use synonyms, homophones, and varied word forms for better associations.
- Challenge yourself to think outside the box and strive for accuracy.

## Motivation
The game stems from the universal appeal of word association games and their potential to enhance cognitive and linguistic skills. It aims to combine fun with education, fostering creativity, expanding vocabulary, and providing players with a tool for intellectual development.

## Links
- **Demo Video:** [Watch here](https://youtu.be/JFLHHBxS72E)

## Developer Information
- **Developer:** Vo Thanh Thong
- **Email:** vothanhthong.work@gmail.com

Enjoy playing NoiTu Game and discover the joy of words!
