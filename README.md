# Bridge - Godot Starter Game

A simple Godot game starter project featuring a movable character sprite on a tilemap world.

## Features

- Player character (blue square) that can move in all directions
- Tilemap-based world with collision detection
- Camera that follows the player
- Keyboard controls (WASD and Arrow keys)

## Requirements

- Godot 4.3 or later

## How to Run

1. Open Godot Engine
2. Click "Import" and select the `project.godot` file in this directory
3. Click "Import & Edit"
4. Press F5 or click the "Play" button to run the game

## Controls

- **W** or **Up Arrow**: Move up
- **A** or **Left Arrow**: Move left
- **S** or **Down Arrow**: Move down
- **D** or **Right Arrow**: Move right

## Project Structure

- `project.godot` - Main Godot project configuration
- `Player.gd` - Player movement script
- `Player.tscn` - Player character scene
- `World.tscn` - Main game world scene
- `tileset.tres` - Tileset resource with collision tiles

## Customization

### Adding Your Own Sprite

1. Import your sprite image into the project
2. Open `Player.tscn` in the Godot editor
3. Replace the ColorRect node with a Sprite2D node
4. Assign your sprite texture to the Sprite2D

### Customizing the Tileset

1. Import your tileset texture
2. Open `tileset.tres` in the Godot editor
3. Replace the PlaceholderTexture2D with your texture
4. Configure tile collisions as needed
5. Open `World.tscn` and paint new tiles on the TileMap

### Adjusting Movement Speed

Edit the `SPEED` constant in `Player.gd` (default is 200.0)
