# Survival Road

A simple endless runner-style driving game built with A-Frame. Stay on the road as long as possible while avoiding holes that appear randomly.

## How to Play

**Objective**  
Drive as far as you can without falling off the road. The road breaks apart over time, creating holes you must steer around.

**Controls**
- **Desktop**: Move your mouse to look around and steer. The car drives forward automatically.
- **Mobile**: Tap the screen to enable pointer lock, then drag your finger to steer.

**Game Flow**
1. A short loading screen appears.
2. Title screen shows with the developer name.
3. **Level 1**: Survive for 30 seconds. The road is relatively forgiving.
4. Automatic transition to **Level 2** (harder mode with darker visuals and more frequent holes). This level is endless.
5. The game ends when your car falls off the road.

**Features**
- The car model visually rotates when you steer.
- Buildings scroll past on both sides of the road.
- Background music plays automatically (use the mute button in the top right).
- When you crash, a Game Over screen appears with your final time and level reached.

**Tips**
- Keep an eye on the road ahead — holes appear suddenly.
- Turning is done by looking left or right.
- Level 2 is significantly harder — expect more gaps.

## Running the Game

The game is hosted on **GitHub Pages**, so no local server is required.

Simply visit the GitHub Pages URL for the repository. All assets (models, sounds, etc.) load directly from the same folder.

**Required Files** (must be in the root of the repository):
- `index.html`
- `car.glb`
- `building1.glb`
- `building2.glb`
- `AchtungPanzer.wav`
- `winSound.mp3`
- `loseSound.mp3`

## Controls Summary

|
 Platform   
|
 Action                  
|
 How to Do It                     
|
|
------------
|
-------------------------
|
----------------------------------
|
|
 Desktop    
|
 Steer                   
|
 Move mouse left/right            
|
|
 Mobile     
|
 Steer                   
|
 Tap screen then drag finger      
|
|
 Both       
|
 Mute/Unmute Music       
|
 Click the 🔊 button (top right)  
|
|
 Both       
|
 Restart after Game Over 
|
 Click "Play Again" button        
|

Enjoy the game!

---

Made with A-Frame • Procedurally generated road with random holes • Custom Blender models and music