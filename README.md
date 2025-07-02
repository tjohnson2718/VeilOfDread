# Veil of Dread

**Veil of Dread** is a Victorian-era horror adventure game developed as a senior capstone project at Neumont College of Computer Science. Set in a fog-drenched gothic city, players must escape a deadly, sound-sensitive creature using stealth, problem-solving, and wit. The game combines dynamic AI systems, immersive level design, and chilling atmosphere to deliver a suspenseful experience.

## 🎮 About the Game

In *Veil of Dread*, players awaken in an abandoned district haunted by a terrifying entity that hunts based on sound. With no weapons and limited resources, survival depends on mastering stealth mechanics, uncovering secrets, and solving puzzles that unlock new paths and abilities. Every footstep could be your last.

### Key Features

- **Sound-Based Enemy AI**: An advanced AI system tracks and responds to sound stimuli in real time, creating dynamic and unpredictable encounters.
- **Dynamic Level Design**: The environment evolves as players progress, with secret passages, interactive puzzles, and hidden upgrades.
- **Inventory System**: Players collect and use items to solve puzzles, unlock new areas, and distract enemies.
- **Immersive Atmosphere**: Developed using Unreal Engine 5 and Blender, the game features eerie lighting, environmental storytelling, and rich audio design.
- **Checkpoints & Progression**: Intelligent checkpoint management ensures smooth gameplay and retry mechanics.

## 🛠️ Technologies Used

- **Unreal Engine 5** – Core development environment
- **Blueprints & C++** – Gameplay systems, AI logic, and custom mechanics
- **Blender** – 3D modeling and animation
- **SDL2, GLM, Assimp** – Supporting libraries for earlier raytracing tools and research
- **Custom Raytracer** – Used for prototyping lighting/reflection logic

## 📁 Project Structure

```bash
VeilOfDread/
│
├── Source/                  # Unreal C++ source files
├── Content/                 # Game assets (meshes, materials, sounds, etc.)
├── Config/                  # Project configuration files
├── Saved/                   # Save data and logs
├── Docs/                    # Design docs, planning, and research notes
├── README.md                # This file
└── .uproject                # Unreal Engine project file

