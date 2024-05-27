# Guess My Number App

## Overview

"Guess My Number" is a fun and interactive mobile game where you try to guess the number chosen by your device. This project is a React Native application written in TypeScript.

## Table of Contents

- Overview
- Features
- Installation
- Running the App
- Project Structure
- Screenshots

## Features

- Start Screen: Enter a number to start the game.
- Game Screen: The app will try to guess your number based on your inputs.
- Game Over Screen: Displays the result and the number of attempts taken by the app.
- Responsive Design: Ensures a smooth experience on both iOS and Android devices.

## Installation

Prerequisites
Node.js (LTS version recommended)
npm or yarn
Expo CLI

- Steps
  Clone the repository:

```bash
Copy code
git clone https://github.com/your-username/guess-my-number.git
cd guess-my-number
```

### Install the dependencies:

```bash
npm install
# or
yarn install
Install Expo CLI globally (if not already installed):
```

```bash
npm install -g expo-cli
# or
yarn global add expo-cli
```

## Running the App

Start the development server:

```bash
expo start
```

Use the Expo Go app on your iOS or Android device to scan the QR code from the terminal or the browser.
Project Structure
go
Copy code
.
├── assets
│ ├── fonts
│ └── images
├── components
│ ├── game
│ │ ├── GuessLogItem.tsx
│ │ └── NumberContainer.tsx
│ ├── ui
│ │ ├── Card.tsx
│ │ ├── InstructionText.tsx
│ │ ├── PrimaryButton.tsx
│ │ └── Title.tsx
├── constants
│ └── Colors.ts
├── screens
│ ├── GameOverScreen.tsx
│ ├── GameScreen.tsx
│ └── StartGameScreen.tsx
├── App.tsx
├── index.tsx
├── tsconfig.json
└── package.json

## Components

- Game Components: Components specific to the game logic and display (e.g., GuessLogItem, NumberContainer).
- UI Components: Reusable UI components (e.g., Card, InstructionText, PrimaryButton, Title).

### Screens

- StartGameScreen: The initial screen where the user enters a number.
- GameScreen: The main game screen where the guessing happens.
- GameOverScreen: The screen displayed when the game is over.

### Constants

- Colors.ts: Contains color constants used throughout the app.
  Screenshots
