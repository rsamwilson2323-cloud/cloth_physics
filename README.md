# 🧵 CLOTH PHYSICS — Interactive Cloth Physics Simulator

> **Experience realistic fabric movement. Simulate physics. Interact with virtual cloth.**
>
> Explore how fabric behaves through an interactive browser-based cloth physics simulation. Observe gravity, wind, stretching, folding, deformation and tearing through real-time animated visualization.
>
> A physics-based educational application built using HTML, CSS, and JavaScript — all inside one standalone HTML file.

---

## ✨ Features

### 🧵 Interactive Cloth Simulation

Experience fabric behavior through an animated physics simulation:

- Real-time cloth movement and deformation.
- Particle-based fabric representation.
- Flexible spring connections between particles.
- Gravity-based fabric movement.
- Realistic-looking stretching and folding.
- Continuous physics calculations.
- Interactive cloth manipulation.

### 🌬️ Physics Controls

Experiment with different physical properties:

- **Gravity** — Control the downward force acting on the fabric.
- **Wind** — Apply directional forces to the cloth.
- **Stiffness** — Adjust fabric flexibility and resistance.
- **Resolution** — Change the number of cloth particles.
- **Physics Simulation** — Observe how forces affect fabric movement.

### 🖱️ Interactive Mouse Controls

- Drag and move fabric particles.
- Stretch the cloth using mouse interaction.
- Manipulate different parts of the fabric.
- Cut or tear fabric connections.
- Observe how the fabric reacts to interaction.

### ⏯️ Simulation Controls

- ▶️ Start the simulation.
- ⏸️ Pause the simulation.
- 🔄 Reset the cloth.
- 🌬️ Adjust wind strength.
- ⚙️ Modify physics parameters.
- 🧵 Experiment with different fabric configurations.

### 🎨 Visualization

- Animated cloth mesh.
- Particle and spring visualization.
- Dynamic fabric deformation.
- Smooth real-time rendering.
- Interactive simulation environment.
- Modern dark-themed interface.

---

## 📂 Project Structure

```text
cloth_physics/
│
├── cloth_physics.html    ← Complete web application
├── README.md             ← Project documentation
└── LICENSE               ← Project license
```

The complete application is contained in a single HTML file, including:

- HTML structure
- CSS styling
- JavaScript physics engine
- Cloth particle system
- Spring constraint calculations
- Animation and rendering logic
- Mouse interaction
- Simulation controls

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rsamwilson2323-cloud/cloth_physics.git
```

### 2️⃣ Open the Project Folder

```bash
cd cloth_physics
```

### 3️⃣ Run the Application

Open `cloth_physics.html` in any modern web browser.

**Windows users:** Double-click the HTML file to launch the simulator in your default browser.

✅ No installation process required.

---

## 📦 Requirements

```text
HTML5             Application structure
CSS3              Styling and animations
JavaScript        Physics engine and interaction
Canvas            Simulation rendering
Modern Browser    Chrome, Edge, Firefox, etc.
```

**No additional dependencies are required.**

- No Python
- No Node.js
- No npm packages
- No database
- No backend server

---

## 🚀 Live Demo

You can publish CLOTH PHYSICS using GitHub Pages.

**Repository:**

https://github.com/rsamwilson2323-cloud/cloth_physics

**Application file:**

https://github.com/rsamwilson2323-cloud/cloth_physics/blob/main/cloth_physics.html

To publish the application:

1. Open the repository's **Settings → Pages**.
2. Select the `main` branch.
3. Choose `/ (root)` as the publishing folder.
4. Click **Save**.

GitHub Pages will generate a website URL after publishing completes.

---

## ▶️ Usage

### 🧵 1. Start the Simulation

1. Open the application.
2. Allow the cloth simulation to initialize.
3. Start the physics simulation.
4. Observe the fabric responding to gravity.

### 🖱️ 2. Interact With the Fabric

1. Move your mouse over the fabric.
2. Click and drag particles.
3. Stretch and deform the cloth.
4. Release the mouse to observe its movement.

### 🌬️ 3. Experiment With Physics

Adjust the available simulation parameters:

- Increase gravity to make the fabric fall faster.
- Increase wind to create stronger fabric movement.
- Change stiffness to experiment with fabric flexibility.
- Adjust resolution to change the particle mesh.

### ✂️ 4. Experiment With Tearing

Use the available tearing interaction to break fabric connections and observe how the cloth structure changes.

### 🔄 5. Reset the Simulation

Reset the simulation to restore the original cloth configuration and experiment again.

---

## 🧠 Physics Behind the Simulation

The cloth simulation demonstrates several fundamental physics concepts.

| Physics Concept | Description |
|---|---|
| Particle System | Represents fabric using connected particles |
| Spring Constraints | Connects particles to maintain fabric structure |
| Gravity | Applies downward acceleration |
| Wind Force | Applies external directional force |
| Verlet Integration | Updates particle positions using previous positions |
| Constraint Solving | Maintains approximate distances between particles |
| Deformation | Changes the fabric's shape under applied forces |
| Tearing | Breaks selected spring connections |

### Mathematical Representation

**Verlet Integration:**

```text
newPosition =
currentPosition
+ (currentPosition - previousPosition)
+ acceleration × time²
```

**Spring Constraint:**

```text
distance = √((x2-x1)² + (y2-y1)²)

correction = distance - restLength
```

These calculations help simulate the movement and deformation of connected fabric particles.

---

## 🛠️ Key Technical Details

| Feature | Implementation |
|---|---|
| Frontend | HTML5 |
| Styling | CSS3 |
| Application Logic | Vanilla JavaScript |
| Physics Engine | Custom JavaScript simulation |
| Physics Integration | Verlet Integration |
| Cloth Structure | Particle-Spring System |
| Rendering | HTML Canvas |
| Interaction | Mouse Events |
| Animation | JavaScript Animation Loop |
| Backend | Not required |
| Database | Not required |

---

## 📌 Important Notes

- CLOTH PHYSICS is designed for educational and experimental purposes.
- The simulation uses a particle-and-spring model to approximate fabric behavior.
- It is not a complete real-world material simulation.
- Actual performance depends on cloth resolution, browser and device capabilities.
- High particle counts may affect performance.
- Wind and gravity are simulated forces.
- The application runs locally in the browser.

---

## 🚀 Future Improvements

- 🌊 Add more realistic wind simulation.
- 🧵 Introduce different fabric materials.
- ✂️ Improve cloth tearing and cutting mechanics.
- 🧊 Add full 3D cloth simulation.
- 💧 Add water interaction and wet fabric effects.
- 🔥 Add heat and fabric deformation experiments.
- 🪡 Add cloth stitching and sewing.
- 🎮 Add interactive cloth challenges.
- 📊 Add real-time physics statistics.
- 🎨 Add fabric color and texture customization.
- 📱 Improve mobile touch controls.
- 🎥 Add simulation recording and replay.

---

## ⚠️ Disclaimer

This project is intended for educational and personal use. It demonstrates fundamental cloth physics concepts through an interactive browser-based simulation.

**CLOTH PHYSICS is an educational physics simulator, not a professional textile engineering or fabric simulation platform.**

---

## 👨‍💻 Author

**Sam Wilson**

🌐 GitHub: https://github.com/rsamwilson2323-cloud

💼 LinkedIn: https://www.linkedin.com/in/sam-wilson-14b554385/

---

## 📜 License

This project is distributed under the license provided in the repository's `LICENSE` file.

---

<div align="center">

### 🧵 CLOTH PHYSICS

**Don't just watch physics. Interact with it.**

*Built with HTML, CSS, and JavaScript.*

</div>
