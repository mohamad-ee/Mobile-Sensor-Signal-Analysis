# Mobile Sensor Signal Analysis (MATLAB)

This project analyzes motion signals recorded using **MATLAB Mobile** and processed inside MATLAB.

### ✅ Main Goals
- Record magnetic / motion sensor data by phone  
- Preprocess the signal and remove noise  
- Convert sampling from **50Hz → 100Hz**  
- Extract and visualize:
  - Single-sided amplitude spectrum (FFT)
  - Dominant frequency
  - Spectrogram
- Compare pendulum/string lengths **(52cm, 77cm, 108cm)** and show how length affects frequency

---

### 📁 Included Files
| File | Description |
|------|-------------|
| `DSP_project.mlx` | Main MATLAB Live Script containing the full analysis |
| `acceleration_77cm.mat` | Sensor log (77cm experiment) |
| `sensor_108.mat` | Sensor log (108cm experiment) |
| `sensorlog_40cm.mat` | Sensor log (40cm experiment) |
| `עיבוד אותות סופי.pdf` | Final signal processing report |

---

### 📊 What the script does
✔ Loads data from the MATLAB Mobile sensor logs  
✔ Filters the signal and performs basic noise removal  
✔ Resamples signal from **50Hz to 100Hz**  
✔ Calculates FFT and dominant frequency  
✔ Displays the **spectrum** and **spectrogram**  
✔ Compares results between different pendulum lengths

---

### 🔧 Requirements
- MATLAB R2021+  
- Signal Processing Toolbox (FFT/spectrogram functions)

---

### ✍ Author
**Mohamad Mashal**  
Electrical & Electronics Engineering  
Specialization: DSP, Communications & Signal Processing  
