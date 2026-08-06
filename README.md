# 🤖 Project Assembly & Exploded View (Onshape)

Welcome to the technical documentation of the assembly and mechanical design structure. This repository outlines the joint configurations and explosion steps implemented in Onshape.
---

## 🔗 Live CAD Model Access

You can view, inspect, and test the assembly and exploded views of the live Onshape model through the link below:
👉 **[Click Here to View and Edit the Live Onshape Model](https://cad.onshape.com/documents/bd7a0bea55eea93531941c04/w/a3c836c2a17439c7137bd585/e/96fb98fe7ebec88bf06825f1)**
---

## ⚙️ Assembly Mates Overview
* **Planar Mate:** Restricts parts to a 2D plane, providing 3 degrees of freedom (2 linear translations along X/Y and 1 rotation around the normal Z-axis). Perfect for sliding components.
* **Fastened & Mechanical Mates:** Used to lock components completely or simulate precise hinges and sliders.
* **Multi-Surface Parallelism:** Achieved by referencing master datum planes or aligning connectors sequentially to avoid over-constraints.

---

## 💥 Exploded Views & Animation Workflow
* **Explode Steps:** Parts are separated into structured individual steps (`Explode step 1`, `Explode step 2`, etc.) to control the sequence and timing of the disassembly.
* **Animation & Recording:** Since Onshape renders exploded views statically for drafting and inspection, real-time screen capture tools are utilized during the explode-collapse preview to generate demonstration videos. Speed and pacing can be further adjusted using external video editors.

---



