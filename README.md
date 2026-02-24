# 🧬 ProViz — Structural Bioinformatics Suite
### **v2.4.1 — BETA**

**ProViz** is a high-performance, web-native structural bioinformatics platform designed to bring 3D molecular visualization and thermodynamic simulations directly to the browser. It bridges the gap between heavy desktop-only software and accessible web tools, offering a "Cyberpunk" aesthetic optimized for modern researchers and students.

---

##  Key Features

###  1. Structure Lab (3D Visualization)
* **Global PDB Search:** Integration with the **RCSB Data API** allows users to fetch any of the 218,000+ known protein structures via 4-character PDB IDs.
* **Multi-Mode Rendering:** Toggle between **Cartoon**, **Surface**, **Stick**, and **Sphere** views using the 3Dmol.js engine.
* **Custom Schematics:** Real-time controls for surface opacity and color schemes including Spectrum, Chain, and Secondary Structure.
* **High-Res Exports:** Generate publication-ready snapshots directly from the viewer.

###  2. Folding Lab (2D Physics Simulation)
* **Real-Time Simulation:** Observe the transition from a Primary random coil to a Native functional state through five distinct phases: Primary, Secondary, Tertiary, Hydrophobic Collapse, and Native.
* **Thermodynamic Funnel:** A live **Gibbs Free Energy ($\Delta G$) Landscape** tracks the protein's journey toward its global energy minimum.
* **Clinical Modeling:** * **Chaperones:** Toggle molecular guardians that stabilize the folding pathway.
    * **Mutations:** Simulate point mutations that lead to misfolding and toxic **Amyloid Aggregates**.
* **X-Ray Vision:** Highlights the emergence of the hydrophobic core during the collapse phase.

###  3. Tool Matrix
* A side-by-side comparative analysis of industry standards like **PyMOL**, **UCSF Chimera**, and **RasMol**, evaluating rendering quality, scripting capability, and ease of use.

---

## 🛠 Tech Stack
* **Core Engine:** 3Dmol.js / Three.js
* **Styling:** Custom CSS focusing on high-contrast "Cyberpunk" aesthetics using **Orbitron** and **JetBrains Mono** fonts.
* **Physics:** Custom spring-mass system with easing functions for molecular bond simulation.
* **Data Hub:** RCSB Protein Data Bank (PDB).

---

##  Installation & Usage

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/tribhuvan-0/ProViz.git](https://github.com/tribhuvan-0/ProViz.git)
    ```
2.  **Open in VS Code:** Open the `proviz.html` file.
3.  **Run with Live Server:**
    * Install the **Live Server** extension in VS Code.
    * Click **"Go Live"** in the status bar at the bottom right.
    * *Note: Using a local server is required to bypass CORS restrictions when fetching protein data from RCSB.*

---

---

## 📜 License
© 2026 ProViz Suite · Academic & Research Use Only.