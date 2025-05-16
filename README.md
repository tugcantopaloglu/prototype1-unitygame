# Unity Game Project

A **third-person 3D game prototype** developed in Unity. This project serves as a **testing ground for core gameplay mechanics**, including player movement, camera behavior, and environmental interaction. It is not a finished game, but rather an experimental setup for future development and learning purposes.

## 🎯 About the Project

This prototype was created to explore and test essential components of a 3D game, such as:

- Character locomotion
- Dynamic camera control
- Collision and terrain interaction
- Basic animation stubs

Some mechanics are **intentionally simplified** or **incomplete**, and may contain experimental code used for learning, prototyping, or iterative development.

## 📌 Key Features

- 🎮 **Third-Person Player Controller**  
  Walk, jump, and rotate the player using keyboard and mouse input.

- 🎥 **Cinematic Camera System**  
  A smooth follow camera that supports player look direction and screen rotation.

- 🗺️ **Simple Environment Setup**  
  A test terrain used to verify movement, physics, and collisions.

- 🔧 **Modular & Test-Oriented Codebase**  
  Scripts are written with readability and future modification in mind.

## 🚀 Getting Started

### Requirements

- Unity 2021.3 LTS or later  
- Unity Input System package (installed via Package Manager)

### Installation Steps

```bash
git clone https://github.com/tugcantopaloglu/unity-game-project.git
```

1. Open the folder in **Unity Hub**.
2. Load the scene located at `Assets/Scenes/MainScene.unity`.
3. Press **Play** to run the prototype.

## 🕹 Controls

| Action       | Input               |
|--------------|---------------------|
| Move         | WASD / Arrow Keys   |
| Look Around  | Mouse Movement      |
| Jump         | Spacebar            |

## 🧩 Project Structure

```
Assets/
├── Scripts/             # Player and camera scripts
├── Scenes/              # Main test scene
├── Prefabs/             # Game objects used for testing
├── Materials/           # Basic material files
└── ...
```

## 🔍 Prototype Notes

- This project is **not intended for production**.
- Some scripts or objects may contain **incomplete logic**, used only to **experiment** with Unity features.
- Code is kept flexible and lightweight for **easy iteration** and further learning.

## 📷 Preview

> *(You can insert demo screenshots or screen captures here, e.g., from Assets/Screenshots/)*

## 💡 Future Plans

- Add Animator Controller for smooth transitions  
- Design basic enemy AI for interactions  
- Extend terrain and introduce obstacles  
- Improve camera behavior and occlusion handling  
- Add UI elements such as HUD, health, or inventory
