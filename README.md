# Trigonometric-PRO---A-L-Toolkit
**Trigonometric PRO** is a comprehensive, interactive, and single-file web-based toolkit meticulously designed to assist Advanced Level (A/L) students and anyone studying trigonometry.

# Trigonometric PRO - A/L Toolkit

## Description

**Trigonometric PRO** is a comprehensive, interactive, and single-file web-based toolkit meticulously designed to assist Advanced Level (A/L) students and anyone studying trigonometry. It consolidates multiple powerful tools into a seamless, user-friendly interface, making it effortless to perform complex calculations, solve geometric problems, and visualize trigonometric concepts. The application is fully responsive, supports both **English** and **Sinhala** languages, and features a sleek, switchable dark/light theme to ensure a comfortable user experience.

Built with vanilla HTML, CSS, and JavaScript, the toolkit leverages high-performance libraries like **Math.js** for the computational engine, **Chart.js** for dynamic graphing, and **Three.js** to deliver a visually stunning 3D loading animation.

---

## Features

This application is organized into five main tabs, each providing a specific and powerful set of functionalities:

### 1. **Advanced Calculator**
   - **Expression Evaluation**: Instantly evaluates complex trigonometric expressions using both degrees (`deg`) and radians (`pi`). Example: `sin(pi/6) + cos(60 deg)^2`.
   - **Equation Solver**: Automatically finds the principal value and the general solution for trigonometric equations. Example: `cos(x) = 0.5`.
   - **Show Method**: Provides a clear, step-by-step breakdown of the method used for direct evaluations and equation solving.
   - **Export Results**: Easily copy the formatted output to your clipboard or download it as a text file.

### 2. **Triangle Solver**
   - **Solve Any Triangle**: Enter any three known values (sides or angles) to compute all remaining sides, angles, the perimeter, and the area of the triangle.
   - **Comprehensive Case Support**: Intelligently solves triangles for SSS (Side-Side-Side), SAS (Side-Angle-Side), and AAS/ASA (Angle-Angle-Side/Angle-Side-Angle) configurations.
   - **Interactive SVG Visualizer**: A dynamic SVG diagram updates in real-time to visually represent the proportions of the solved triangle, providing an intuitive geometric reference.

### 3. **Function Grapher**
   - **Multi-Function Plotting**: Graph one or more trigonometric functions on the same set of axes by separating them with a comma. Example: `sin(x), 1 - cos(x)^2`.
   - **Fully Interactive Chart**: Seamlessly pan and zoom the graph using mouse or touch gestures to explore function behavior in fine detail.
   - **Automated Function Analysis**: Instantly generates a detailed explanation of key properties for plotted functions, including **Amplitude, Period, Phase Shift, Domain, Range, and Vertical Asymptotes**.
   - **Download Graph**: Save the generated chart as a high-quality PNG image for your notes or reports.

### 4. **Wave Simulator**
   - **Real-Time Wave Control**: Interactively manipulate trigonometric waves using intuitive sliders to adjust **Amplitude, Frequency, Phase Shift, and Vertical Shift**.
   - **Wave Superposition**: Enable the "Sum of Waves" feature to add a second, independently controlled wave. Visualize how the two waves interfere to produce a resultant wave, all updated in real-time.
   - **Live Formula Display**: A dynamic formula display updates instantly to reflect the exact mathematical equation of the wave(s) you are creating.
   - **Supports All 6 Trig Functions**: Generate and combine waves using sin, cos, tan, csc, sec, and cot functions for advanced exploration.

### 5. **Identity Verifier**
   - **Prove Trigonometric Identities**: Enter expressions for the Left-Hand Side (LHS) and Right-Hand Side (RHS) to rigorously check if they form a valid trigonometric identity.
   - **Robust Numerical Verification**: The tool tests the identity by evaluating both sides with a large number of random inputs, determining its validity with a high degree of confidence.
   - **Show Transformation**: Clearly displays how the input expressions are normalized and parsed by the mathematical engine before the verification process begins.

---

## Tech Stack

*   **Frontend**: HTML5, CSS3, JavaScript (ES6+ Module Pattern)
*   **Mathematical Engine**: [Math.js](https://mathjs.org/)
*   **Charting Library**: [Chart.js](https://www.chartjs.org/) with the [chartjs-plugin-zoom](https://www.chartjs.org/chartjs-plugin-zoom/latest/) for interactivity
*   **3D Graphics**: [Three.js](https://threejs.org/) (powering the 3D loading animation)

---

## How to Use

No installation or complex setup is required. The entire application is self-contained in a single file.

1.  Clone the repository or download the `trigo.html` file.
2.  Open the `trigo.html` file in any modern web browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge).
3.  The application will initialize with a 3D loading animation and will be ready for use.

---

## Author

*   **Sadeepa Lakshan**

---

## License

This project is open source. Feel free to use, modify, and distribute it for educational or personal purposes.
