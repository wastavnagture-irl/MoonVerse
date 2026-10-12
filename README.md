# MoonVerse

An immersive 3D web experience inspired by moonlit oceans, celestial skies, and interactive romantic scenes.

## Overview
MoonVerse is a browser-based visual experience combining 3D scenes, animated particles, atmospheric lighting, and interactive moments to create a cinematic atmosphere.

## Highlights
- 3D ocean and moonlit horizon
- Star-filled sky and celestial effects
- Themed scenes featuring aurora, lanterns, petals, and meteor effects
- Interactive visual elements
- Particle and shader-based effects
- Bloom post-processing
- Procedural audio created with the Web Audio API
- Interactive poetry/card elements and cursor effects

## Built With
- HTML
- CSS
- JavaScript (ES modules)
- [Three.js](https://threejs.org/)
- Three.js add-ons such as OrbitControls, Water, and post-processing effects
- Web Audio API

## Run Locally
Because the project uses JavaScript modules, run it through a local development server rather than opening the HTML file directly.

For example, if Python is installed:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser and navigate to the project page.

## Project Structure
```text
moonverse/
├── index.html
└── README.md
```
The current version may keep CSS and JavaScript inside the HTML file. Update this section if you split the code into separate files.

## What I Practiced
- Building a scene with Three.js
- Working with camera controls and 3D objects
- Creating atmospheric visual effects
- Using particles and custom shader effects
- Adding post-processing effects
- Generating sound procedurally in the browser
- Combining multiple interactive elements into one experience

## Performance Notes
Rendering cost depends on device, browser, resolution, and active effects. Test on desktop and mobile before making specific FPS claims.

## Future Improvements
- Add quality settings for lower-powered devices
- Improve mobile controls and responsive behavior
- Add a reduced-motion option
- Profile and optimize shader and particle workloads
- Test across major browsers

## Author
**Wastav Nagture**  
GitHub: [@wastavnagture-irl](https://github.com/wastavnagture-irl)
