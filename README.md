# Multiple-3D-Window

A Three.js implementation that creates a seamless 3D scene spanning across multiple browser windows using localStorage for synchronization.

## Demo

Open multiple browser windows to see 3D objects move seamlessly between them - each window acts as a viewport into a shared 3D world.

## Features

- **Multi-Window Sync**: 3D scene synchronized across browser windows using localStorage
- **Three.js Graphics**: Smooth 3D rendering with WebGL
- **Responsive**: Adapts to different window sizes and positions

## Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shivas1432/Multiple-3D-Window.git
   cd Multiple-3D-Window
   ```

2. **Install http-server (if needed):**
   ```bash
   npm install -g http-server
   ```

3. **Start the server:**
   ```bash
   http-server
   ```

4. **Open the application:**
   - Navigate to `http://127.0.0.1:8080` in your browser
   - Open the same URL in multiple windows/tabs
   - Arrange windows to see the multi-window effect

## How It Works

Each browser window displays a portion of a larger 3D scene. Objects appear to move naturally between windows by:
- Using localStorage to sync object positions across windows
- Calculating each window's camera position based on screen coordinates
- Rendering the appropriate view of the shared 3D world

## Browser Compatibility

Works in all modern browsers that support WebGL and localStorage.

## License

MIT License