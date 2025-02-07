# 🌹 3D Rose Plot in MATLAB

## 🌟 Overview
This MATLAB script generates a **3D rose plot** using parametric equations. It creates a beautiful, petal-like structure using **polar coordinates** and **surface plotting** techniques.

---

## 🔑 Features
- **Uses Polar Coordinates** – Converts radial and angular components to 3D Cartesian coordinates.
- **Customizable Petal Shape** – Allows adjustment of the number of petals per cycle.
- **Smooth Rendering** – Uses `surf()` with no lines for a clean look.
- **Red Color Mapping** – Simulates realistic rose coloring.
- **Adjustable View Angle** – Provides a 3D visualization.

---

## 📸 Preview
![3D Rose](https://github.com/user-attachments/assets/c27f1b54-c63f-4c35-929f-05c40502becc)


---

## 📌 How It Works
1. **Define Parameters**:
   - `n`: Number of points for resolution.
   - `A, B, C`: Constants that define petal shape.
   - `r, theta`: Radial and angular components.

2. **Generate the Petal Shape**:
   - Uses a parametric function to modify the surface curvature.
   - `phi` controls the rotation of the petals.

3. **Convert to 3D Coordinates**:
   - Computes `X, Y, Z` from transformed polar coordinates.

4. **Plot the Surface**:
   - Uses `surf()` to render a 3D shape.
   - Applies a **red colormap** for a realistic rose effect.

---

## 📌 Usage Instructions
1. Open MATLAB and copy the script into a new `.m` file.
2. Run the script to generate the **3D rose plot**.
3. Adjust the parameters (`petalNum`, `A`, `B`, `C`) for different variations.

---

## 🎯 Future Improvements
- 🌸 Add interactive controls to modify petal shape in real-time.
- 🌈 Experiment with different color mappings for diverse rose colors.
- 🔄 Animate the rotation of the rose for a dynamic effect.

---

## 🎓 Credits
Developed by **MATLAB Enthusiasts** 🏆

---

Enjoy visualizing your **3D rose in MATLAB**! 🌹💻

