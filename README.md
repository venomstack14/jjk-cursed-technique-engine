# JJK: Real-Time Cursed Technique Engine 

An interactive, premium WebGL and Computer Vision application that utilizes MediaPipe Hand Tracking and Three.js to manifest iconic Jujutsu Kaisen cursed techniques based on physical hand gestures. 

This project maps complex geometric particle fields dynamically around the user's hands in real time via an optimized single-file web deployment.

---

##  Key Technical Enhancements
While building this iteration, several layout behaviors and structural optimizations were implemented to improve the core execution:

* **Structural Coordinate Anchor:** Implemented an absolute orientation lock on the global `particles.rotation` matrix inside the main animation loop. This prevents layout drift and freezes coordinate axes cleanly during specific Domain Expansions.
* **Torus Singularity Integration:** Upgraded the `getShrine` spatial generator function to calculate a 3D parametric Torus Knot ($p=2, q=3$) array, creating a dense crimson core anomaly inside the technique structure.
* **Responsive Viewport Scaling:** Enhanced the Three.js resizing logic to dynamically update projection matrices and post-processing composer bounds, ensuring fluid performance across varying screen aspect ratios.

---

##  Gestures & Techniques Included

| Hand Gesture | Activated Technique | Visual Profile |
| :--- | :--- | :--- |
| **Default / Rest** | Neutral State | Soft cyan ambient cursed energy aura fields |
| **Pointer Finger Up** | Reverse Cursed Technique: Red | High-velocity linear energy stream with compression core |
| **Two Fingers Up** | Domain Expansion: Infinite Void | Expansive neon space anomaly field with perimeter ring |
| **Pinch Gesture** | Secret Technique: Hollow Purple | High-density collapsing spatial rupture singularity |
| **Open Palm** | Domain Expansion: Malevolent Shrine | Locked environmental framework anchored with a central vortex |

---

##  Tech Stack & Dependencies
* **Core Engine:** HTML5, CSS3, JavaScript (ES6 Modules)
* **Graphics:** [Three.js](https://threejs.org/) (r160)
* **Post-Processing:** WebGL EffectComposer, RenderPass, and UnrealBloomPass
* **Computer Vision:** Google MediaPipe (Camera Utils, Hands, Drawing Utils)

---

##  Credits & Attribution
This project was developed as an independent optimization and creative coding exploration. It is heavily inspired by and builds upon the excellent front-end hand-tracking UI concepts pioneered by [@reinesana](https://github.com/reinesana). 

##  License
This project is open-source and available under the **MIT License**. Feel free to fork, experiment, and expand upon the particle math controllers!
