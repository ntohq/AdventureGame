AdventureGame/
├── project.godot                  # Root config file
├── .github/                       # GitHub Actions, workflows
├── assets/                        # Scene-based folders (exclusive resources)
│   ├── main/                      # Entry point scene
│   │   ├── main.tscn
│   │   ├── main_controller.gd
│   │   └── transition_anim.tres
│   ├── menu/                      # Game menu UI
│   │   ├── menu.tscn
│   │   ├── menu_controller.gd
│   │   ├── background.png
│   │   └── button_start.tres
│   ├── player/                    # Player scene and assets
│   │   ├── player.tscn
│   │   ├── player_controller.gd
│   │   └── player.gltf
│   ├── enemies/                   # Enemy variants
│   │   ├── goblin/
│   │   │   ├── goblin.tscn
│   │   │   └── goblin.gltf
│   │   ├── troll/
│   │   │   ├── troll.tscn
│   │   │   └── troll.gltf
│   │   └── shared/
│   │       ├── enemy_ai.gd
│   │       └── enemy_material.tres
│   ├── ui/                        # Reusable UI components
│   │   ├── health_bar.tscn
│   │   └── dialogue_box.tscn
│   └── levels/                    # Game levels
│       ├── level_01.tscn
│       └── level_02.tscn
├── src/                           # Shared logic, systems, and utilities
│   ├── game_state.gd              # Global game state manager
│   ├── scene_manager.gd          # Handles transitions and orchestration
│   ├── save_manager.gd           # Save/load system
│   ├── input_handler.gd          # Centralized input mapping
│   └── utils/
│       ├── math_utils.gd
│       └── string_utils.gd
├── resources/                     # Global/shared resources
│   ├── fonts/
│   ├── shaders/
│   └── audio/
├── README.md

