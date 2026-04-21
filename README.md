# 🏛️ Virtual Campus Open Day (MVP)

An immersive, cross-platform 3D exploration application designed to bring the campus experience directly to prospective students. 

This project utilizes real-world photogrammetry and 3D building scans, heavily optimized for performance, to create a navigable virtual environment. Built in **Unreal Engine 5**, the application features a dynamic "Dual-Pawn" system that seamlessly supports both fully immersive standalone VR headsets and standard flat-screen devices (PC/Mobile) without requiring different builds.

## ✨ Key Features
* **True-to-Scale 3D Environments:** High-fidelity architectural scans processed through Blender for severe decimation and retopology to ensure smooth performance.
* **Hybrid Cross-Platform Support:** * **VR Mode:** Native teleportation locomotion and hand-tracking support for standalone headsets (e.g., Meta Quest).
* **Flat-Screen Mode:** Standard WASD/Mouse first-person controls and mobile virtual joysticks for users without VR hardware.
* **Optimized for Mobile Render Pipelines:** Forward shading and pre-baked lighting to maintain high framerates on mobile VR chips (Snapdragon XR2) and standard smartphones.

## 🛠️ Tech Stack & Tools
* **Game Engine:** Unreal Engine 5 (Mobile/Tablet Target Hardware)
* **3D Pipeline:** Photogrammetry generation & LiDAR -> Blender (Centering, Scaling, Decimation) -> `.fbx` export
* **Version Control:** Git & GitHub (with Git Large File Storage)
* **Methodology:** Agile (XP) aiming for a 6-month MVP delivery.

---

## 🚀 Getting Started for Developers

**⚠️ IMPORTANT: You MUST have Git LFS installed before cloning this repository. If you clone without LFS, the massive binary `.uasset` and `.umap` files will corrupt.**

### 1. Initial Setup
1. Download and install [Git LFS](https://git-lfs.com/).
2. Open your terminal and initialize LFS on your machine:
   ```bash
   git lfs install
