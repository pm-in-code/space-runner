# BRAYN Space Survival Game

A neon-styled space survival game built with vanilla JavaScript and Canvas 2D.

## 🎮 Play the Game

**[Click here to play!](https://pm-in-code.github.io/space-runner/)**

## 🚀 Features

- **60-second survival challenge** with quiz collision system
- **BRAYN neon aesthetic** with glassmorphism UI
- **Speed scaling** - game accelerates every 10 seconds
- **Quiz system** - answer questions when hitting meteors to avoid losing lives
- **Mobile controls** with virtual joystick and boost button
- **WebAudio music system** with file upload support
- **24 built-in quiz questions** covering logic, soft skills, and space facts
- **Object pooling** for 60 FPS performance optimization

## 🎯 How to Play

1. **Survive for 60 seconds** while avoiding meteors
2. **When you hit a meteor**, answer the quiz question correctly to avoid losing a life
3. **Collect bonuses**: ⚡ Boost (speed enhancement) and ♥ Life (extra life)
4. **Controls**:
   - **Desktop**: WASD/Arrow keys to move, Space/Shift for boost
   - **Mobile**: Virtual joystick and boost button
   - **Quiz**: Keys 1-4 or click to answer

## 🎨 BRAYN Visual Style

- Deep space background (#0B0F1A)
- Neon colors: Cyan (#22E1FF), Blue (#5B8CFF), Magenta (#FF3FD1), Purple (#7A5CFF)
- Glassmorphism UI with blur effects
- Procedural starfield with parallax
- Geometric spaceship with particle trails

## 🔧 Technical Details

- **Vanilla JavaScript** - No external dependencies
- **Canvas 2D** rendering with DPR scaling
- **WebAudio API** for music and sound effects
- **Object pooling** for meteors, bonuses, and particles
- **localStorage** for high scores and settings
- **Mobile responsive** design

## 🎵 Audio

- Generative space ambient music by default
- Upload your own music files via "Load Music" button
- Separate volume controls for music and SFX
- WebAudio-based sound effects for all game events

## 🐛 Debug Features

Press **D** to toggle debug overlay showing:
- FPS counter and performance metrics
- Object counts and draw calls
- Speed level and effects status
- Collision visualization toggle
- Slow motion mode
- Particle system toggle

---

**Built with ❤️ using Canvas 2D and WebAudio API**
