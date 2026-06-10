# 🐸 Kill the Frog Game

## 🎮 Overview

Kill the Frog is a 2D reaction-based mini-game developed in Unity where frogs randomly appear on the screen and the player must click on them before they disappear. The goal is to earn as many points as possible by tapping or clicking on frogs within their lifetime. The project demonstrates core Unity concepts including prefab instantiation, collision detection, UI integration, and automated spawning mechanics.

## 🧠 Game Features

- **Random Frog Spawning**: Frogs appear at random positions on the screen at timed intervals using FrogSpawner.cs
- **Click-to-Kill Mechanic**: Each frog has a Box Collider 2D that detects mouse clicks via OnMouseDown()
- **Auto-Destruction**: Frogs automatically disappear after 2.5 seconds if not clicked (missed opportunity)
- **Scoring System**: Each successful click increases the score by 10 points, displayed in real-time via Unity's UI Text
- **Gravity Physics**: Frogs are affected by gravity (Rigidbody 2D with Gravity Scale 0.3), making them fall slowly
- **Event System**: Proper input handling with Unity's EventSystem for reliable click detection

## 🧰 Tools & Technologies

- Unity Engine (Version 6000.2.6f2 / 6000.4.10f1)
- C# Scripting
- Unity UI System (TextMeshPro)
- Box Collider 2D & Rigidbody 2D Physics
- Sprite Renderer for 2D Graphics


## 🚀 How to Play

1. Open the project in Unity
2. Press the Play button
3. Frogs spawn automatically every 2 seconds
4. Click on each frog before it disappears (2.5 seconds)
5. Each hit adds 10 points to your score

## 🎯 Controls

| Action | Input |
|--------|-------|
| Kill Frog | Left Mouse Click on frog |
| Start Game | Press Play in Unity |
| Restart | Stop and Play again (or Restart button if implemented) |

## 📈 Learning Outcome

This project demonstrates fundamental Unity development concepts including:
- Prefab instantiation and object pooling
- 2D physics with Rigidbody and Collider components
- Mouse input detection using OnMouseDown()
- UI integration with real-time score updates
- Automated spawning using InvokeRepeating()
- Scene management and GameObject lifecycles

This forms a solid foundation for more advanced 2D game projects such as tower defense, clicker games, or arcade-style reaction games.

## 📂 GitHub Repository

Clone or download this repository to explore the project files:
https://github.com/serahthiaka/KillTheFrog-Game.git

## 👨‍💻 Author

SERAH NJOKI THIAKA
Game Development Assignment 1

---

*Frogs are not actually harmed in the making of this game.* 🐸💚
