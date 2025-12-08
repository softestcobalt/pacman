# Pac-Man 2D --- Minimalist README

### Author: Bohdan Yarovenko

### Course: Games Design & Development, Kerry College

### Engine: Unity 2D

------------------------------------------------------------------------

## 🎮 About the Project

Pac-Man 2D is an educational Unity project developed as part of the
Games Design & Development course at Kerry College.\
The goal is to recreate the core mechanics of the classic Pac-Man arcade
game while demonstrating understanding of game design, AI behavior,
gameplay structure, and clean project organization.

------------------------------------------------------------------------

## 🧩 Features

-   Tilemap-based maze\
-   Smooth grid-based movement system\
-   Four ghosts with separate behaviour (Chase / Scatter / Frightened /
    Home)\
-   Collectible pellets and power pellets\
-   Scoring system\
-   Lives and Game Over screen\
-   Minimal, clean pixel-art visual design

------------------------------------------------------------------------

## 📁 Project Structure

A minimalistic overview of the Unity `Assets/` folder:

    Assets/
     ├── Fonts/
     │    └── Retro Gaming.ttf
     ├── Physics/
     │    └── ZeroFriction.physicsMaterial2D
     ├── Prefabs/
     │    ├── Pacman.prefab
     │    ├── Ghost_Blinky.prefab
     │    ├── Ghost_Pinky.prefab
     │    ├── Ghost_Inky.prefab
     │    ├── Ghost_Clyde.prefab
     │    ├── Pellet.prefab
     │    └── PowerPellet.prefab
     ├── Scenes/
     │    └── Pacman.unity
     ├── Scripts/
     │    ├── AnimatedSprite.cs
     │    ├── GameManager.cs
     │    ├── Movement.cs
     │    ├── Pacman.cs
     │    ├── Ghost.cs
     │    ├── GhostBehavior.cs
     │    ├── GhostChase.cs
     │    ├── GhostScatter.cs
     │    ├── GhostFrightened.cs
     │    ├── GhostHome.cs
     │    ├── GhostEyes.cs
     │    ├── Node.cs
     │    ├── Passage.cs
     │    ├── Pellet.cs
     │    └── PowerPellet.cs
     └── Sprites/
          ├── Pacman sprites
          ├── Ghost sprites
          ├── Vulnerable sprites
          ├── Wall tiles
          └── Pellet sprites

------------------------------------------------------------------------

## ▶️ How to Run

1.  Open the project in Unity (2021+ or Unity 6 recommended).\

2.  Load the scene:

        Assets/Scenes/Pacman.unity

3.  Press **Play**.

------------------------------------------------------------------------

## 🌐 WebGL Build

A WebGL version can be exported using Unity Build Profiles and uploaded
to itch.io for browser-based play.

------------------------------------------------------------------------

## 🧪 Possible Improvements

-   More accurate ghost AI mirroring the original game\
-   Level progression system\
-   Sound effects and retro UI polish\
-   High‑score saving\
-   Mobile controls

------------------------------------------------------------------------

## 👨‍💻 Author

**Bohdan Yarovenko**\
Games Design & Development Student\
Kerry College

------------------------------------------------------------------------

## 📜 Educational Use Notice

This project is created strictly for learning purposes.\
Pac-Man is a registered trademark of Bandai Namco.\
This project is a non-commercial student recreation.
