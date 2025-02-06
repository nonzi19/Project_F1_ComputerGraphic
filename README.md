# Interactive 3D Object using JavaScript and GLSL (WebGL Environment)

This project demonstrates an **interactive 3D object** built using **JavaScript** and **GLSL** within a **WebGL environment**. The application provides users with controls to manipulate the object and its hierarchical components in real-time, showcasing the capabilities of WebGL for interactive 3D graphics in the browser.

## Features

### 3D Visualization
- A detailed 3D model of a vehicle with various components, including:
  - Chassis
  - Wheels
  - Rear spoiler
- Rendered using WebGL, leveraging GLSL shaders for lighting, materials, and transformations.

### User Interaction
- **Transformations**:
  - Move the parent object along the X, Y, and Z axes using sliders.
  - Control camera movement to adjust the view angle and zoom level.
- **Hierarchical Transformations**:
  - Apply transformations to specific parts of the model:
    - **Parent**
    - **Child**
    - **Grandchild**
  - Adjustable speed for grandchild transformations.
- **Reset Functionality**:
  - Reset rotations or other transformations to their default state.

### Real-Time Rendering
- Interactive inputs update the 3D scene dynamically.
- Smooth animations and responsive UI enhance the user experience.

## Getting Started

### Prerequisites
To run this project, you'll need:
- A modern web browser with WebGL support.
- A basic understanding of JavaScript and WebGL is helpful for customization.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nonzi19/interactive-3d-webgl.git
   ```
2. Navigate to the project directory:
   ```bash
   cd interactive-3d-webgl
   ```
3. Open the `Project F1.html` file in your web browser:
   - You can simply double-click the file to open it in your default browser.
   - Make sure the file js. also in same file to open it
   - Alternatively, you can serve it locally using an HTTP server. For example:
     ```bash
     python -m http.server
     ```
     Then, navigate to `http://localhost:8000/Project%20F1.html` in your browser.

### Usage
1. Use the sliders to control transformations and camera movement.
2. Select the part of the hierarchy (Parent, Child, or Grandchild) to apply specific transformations.
3. Adjust the transformation speed for the grandchild object as needed.
4. Experiment with the controls to explore the 3D object interactively.

## Built With

- **JavaScript**: For managing the WebGL canvas and user interface interactions.
- **GLSL**: For shader programming, including lighting and rendering effects.
- **WebGL**: To handle the rendering pipeline for the 3D scene.

## Screenshot
![image](https://github.com/user-attachments/assets/83d890bc-50a3-40e1-ad12-e8c421d6d736)

## Potential Applications
- Educational tools for teaching 3D transformations and WebGL programming.
- Interactive 3D visualizations or configurators.
- Prototypes for browser-based 3D applications.

## Future Improvements
- Add more complex 3D models with textures.
- Implement lighting options (e.g., directional, point, or spotlights).
- Include options for scaling and rotation transformations.
- Support for exporting the 3D scene as a file.

## Acknowledgments
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API) for WebGL documentation.
- [Three.js](https://threejs.org/) inspiration for understanding 3D object hierarchy.

