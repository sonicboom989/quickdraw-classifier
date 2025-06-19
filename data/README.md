# 🎨 QuickDraw Dataset

This folder is meant to store the hand-drawn sketch `.npy` files from the [Google Quick, Draw! Dataset](https://quickdraw.withgoogle.com/data). These files are **not included in this repository** due to GitHub's file size limitations.

## 📥 How to Download

1. Go to the official [QuickDraw data download page](https://quickdraw.withgoogle.com/data).
2. Scroll to the **"Full Numpy Bitmaps"** section.
3. Download the following files (used in this project):
   - `full_numpy_bitmap_banana.npy`
   - `full_numpy_bitmap_bicycle.npy`
   - `full_numpy_bitmap_bridge.npy`
   - *(add any others you’re using)*

4. Place them into this `data/` directory.

## 📐 Format

- Each `.npy` file contains **70,000 grayscale images**
- Shape: `(70000, 784)` where each row is a **flattened 28x28** image
- Pixel values range from **0 to 255**

## ⚠️ Note

These files are **ignored by Git** (see `.gitignore`) to keep the repo size manageable. Make sure to manually download them before training the model.

