# Flappy Bird Game

A classic Flappy Bird game built with vanilla JavaScript and HTML5 Canvas. This is a complete, playable implementation with modern styling and smooth gameplay.

## 🎮 Features

- **Smooth Gameplay**: 60 FPS animation with responsive controls
- **Physics Engine**: Realistic bird physics with gravity and rotation
- **Procedural Pipes**: Randomly generated pipe obstacles
- **Score System**: Current score and best score tracking with local storage
- **Visual Effects**: Animated clouds, gradient backgrounds, and smooth animations
- **Responsive Design**: Works on desktop and mobile devices
- **Multiple Input Methods**: Keyboard (SPACE), mouse click, and touch support

## 🚀 How to Play

1. **Start the Game**: Click the "Start Game" button or press SPACE
2. **Control the Bird**: Press SPACE, click, or tap to make the bird flap upward
3. **Avoid Pipes**: Navigate through the gaps in the pipes
4. **Score Points**: Each pipe you pass gives you 1 point
5. **Don't Hit**: Avoid hitting pipes, the ground, or the top of the screen

## 🎯 Game Controls

- **SPACE** - Flap upward
- **Mouse Click** - Flap upward
- **Touch** - Flap upward (mobile devices)
- **Start/Restart Buttons** - Begin new game

## 📁 File Structure

```
flappy-bird/
├── index.html      # Main HTML file with game structure
├── style.css       # Modern CSS styling and responsive design
├── game.js         # Complete game logic and mechanics
└── README.md       # This documentation file
```

## 🛠️ Technical Details

### Game Engine
- **Canvas API**: HTML5 Canvas for rendering
- **RequestAnimationFrame**: Smooth 60 FPS game loop
- **Object-Oriented Design**: Clean, maintainable code structure

### Game Mechanics
- **Bird Physics**: Gravity, velocity, and rotation
- **Collision Detection**: Precise hitbox calculations
- **Pipe Generation**: Procedural obstacle creation
- **Score Tracking**: Local storage for persistent high scores

### Visual Features
- **Gradient Backgrounds**: Sky and ground gradients
- **Animated Clouds**: Moving background elements
- **Bird Animation**: Rotation based on velocity
- **Modern UI**: Clean, responsive interface

## 🎨 Customization

You can easily customize the game by modifying these parameters in `game.js`:

```javascript
// Bird properties
this.bird = {
    gravity: 0.5,        // Gravity strength
    jumpPower: -8,       // Jump force
    // ... other properties
};

// Pipe properties
this.pipeWidth = 60;     // Width of pipes
this.pipeGap = 150;      // Gap between top and bottom pipes
this.pipeSpacing = 200;  // Distance between pipe pairs
this.pipeSpeed = 2;      // How fast pipes move
```

## 🌐 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Getting Started

1. **Download/Clone** the project files
2. **Open** `index.html` in your web browser
3. **Start Playing** immediately - no installation required!

## 🎯 Game Tips

- **Timing is Key**: Don't flap too frequently or too rarely
- **Stay Centered**: Try to keep the bird in the middle of the screen
- **Anticipate**: Look ahead to the next pipe
- **Practice**: The game gets easier with practice!

## 🔧 Development

To modify or extend the game:

1. **Add New Features**: Extend the `FlappyBird` class
2. **Modify Graphics**: Update the drawing methods in `game.js`
3. **Adjust Difficulty**: Change physics parameters
4. **Add Sound**: Implement audio using Web Audio API
5. **Add Animations**: Enhance visual effects

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

---

**Enjoy playing Flappy Bird!** 🐦✨
