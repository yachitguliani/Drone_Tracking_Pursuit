# Drone_Tracking_Pursuit
# Drone Tracking & Pursuit Simulations

This repository contains two Python-based drone simulation projects:

1. **Extended Kalman Filter (EKF) Drone Tracking**  
   A simulation where a drone estimates the position and speed of a moving target using range-only measurements and an Extended Kalman Filter.

2. **Drone Pursuit Simulation**  
   A simulation where a chaser drone attempts to intercept a moving target using basic pursuit logic.

Both simulations include animated visualizations saved as `.mp4` files.

---

---

## 🚀 Features

### EKF Drone Tracking
- Random enemy movement within a defined range.
- Drone moves toward estimated target position.
- Range measurements with Gaussian noise.
- Extended Kalman Filter for estimating target position & velocity.
- Visualizations:
  - True target path
  - Drone path
  - EKF estimated path
  - Range circles
  - Speed comparison over time

### Drone Pursuit Simulation
- Chaser heads directly toward the moving target.
- Target moves with slight random deviations.
- Stops when the target is captured (within set radius).
- Visualizations:
  - Paths of chaser & enemy
  - Distance over time
  - Capture notification

---

## 🛠 Requirements

Install required dependencies:
```bash
pip install numpy matplotlib


