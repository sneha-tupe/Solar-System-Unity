# Solar System Unity Project

An interactive 3D Solar System simulation built in Unity featuring all eight planets, realistic orbital rotations, dual camera views, a comet spawner, and 3D spatial audio.

---

## 🌟 Key Features

* **Complete Solar System:** Includes all 8 planets (Mercury through Neptune) with custom textures, materials, and scaled orbital rotation speeds.
* **Dual Camera System:**
  * **Main Camera:** Framed perspective view capturing the full planetary expanse.
  * **Minimap Camera:** Top-down orthographic tracking camera displaying real-time planetary orbits.
* **3D Spatial Audio:** Environmental drone audio applied to celestial bodies that dynamically fades based on camera proximity.
* **Comet Spawner:** Automated spawner instantiating moving comets across the planetary orbital plane.

---

## 🛠️ Project Structure

* **`Assets/Materials`**: Custom materials mapping planet textures to sphere meshes.
* **`Assets/Prefabs`**: Reusable prefabs including comets and spawner components.
* **`Assets/Scripts`**: C# scripts handling object rotation (`RotateAround`), targeting (`LookAtTarget`), and spawning logic (`Spawner`).
* **`Assets/Sounds`**: Atmospheric audio clips mapped across planets.
* **`Assets/Textures`**: High-resolution surface textures for stars and planets.

---

## 🎮 Playable Demo

You can play the WebGL build directly in your browser:
👉 **[Play Solar System on itch.io](https://niico-96.itch.io/solar-system)**

---

## 👤 Author

* **Created by:** Sneha Tupe
