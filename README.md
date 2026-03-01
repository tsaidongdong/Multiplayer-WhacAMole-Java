# Multiplayer-WhacAMole-Java
A multiplayer, networked arcade game developed in **Java**. This project features a **Client-Server architecture** that allows two players to compete in real-time over a network, featuring synchronized gameplay and integrated sound effects.

## 🌟 Key Features

* **Multiplayer Connectivity:** Built using **Java Socket Programming** for real-time interaction between Server and Client.
* **Dynamic Gameplay:** Includes both a **Single-player mode** and a **Networked competitive mode**.
* **Multithreaded Performance:** Utilizes `Thread` and `TimerTask` to handle concurrent game logic, mole popping, and network communication.
* **Audio Integration:** Features background music and hit sound effects (`.wav`) for an immersive experience.

## 🏗️ System Architecture

The project is structured into several core components:
* **Server Side:** Manages game state and synchronizes data with the connected player.
* **Client Side:** Handles user input and displays the real-time game interface.
* **Event Handling:** Implements custom mouse listeners (`MyMouseEvent`) for precise hit detection.

## 🛠️ Technical Stack

* **Language:** Java
* **Networking:** Java Sockets (TCP/IP)
* **Concurrency:** Java Multi-threading
* **Audio:** Java Sound API

## 📂 File Structure

* `Server.java` / `Client.java`: The backbone of the networked gameplay.
* `SingleVersion.java`: Offline mode implementation.
* `Music.java`: Controller for background music and sound effects.
* `background.wav` / `get.wav`: Audio assets for the game.
