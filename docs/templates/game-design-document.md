## Change Log
### Physical Protype
The initial version of my game was really different. We had the same board and number tiles, and the movement of the guards was still the same but the dice roll changed. At the physical prototype we had a dice roll (1-6), and the player had no control on their movement. The randomness was too heavy in here, and it reduced the player agency. When I showed the game physically, I saw some mistakes as the player felt too frustrated and had some negative reviews about the game. Most of the things were that the game didn’t have enough decision making options and it was too random. 

### Testing Feedback (Design Improvements)
Based on the feedback of testing the physical prototype I realized that the game needed some changes to improve player control, be less random and more strategic decisions. We changed the six faced dice into two dice. One the safe roll dice (1-4), and the other the risk dice roll (3-6), this gives the player choose what type of dice they want to take and have some type of strategy depending on the position. 
The item system was structured into two clear categories: escape items and trap items. Thai was created so it was also a strategic decision on what item to use, since they also have decisions on what item to choose when they land on item tile and to choose what item they want to escape from guards or traps.
We also included a trap mechanic where players could interact directly with their opponent and make the game more strategic.

### Digital Prototype
In the digital version we define the game systems with all the changes that we had from the feedback. The gameplay was made to work consistently and have a specific game loop. The guards were placed with their respective paths and we included to have the right visual as arrows icons to show where each guard would move next. A structured turn system was implemented, ensuring the consistent sequence between player actions and guard movement. 
We also included that guard move twice after every third round to increase the tension of the game. We included an item acquisition system where players need to pick from 2 items where they landed on an item tile. We also change the whole design from where it started by adding more assets to increase the immersion of the players. For last we change the cards to have names of ninja tools like bomb smoke or katana, same for tramps, and that the actions of each item were different and be in respect to work as an actual ninja tool.  


# The Ninja Escape

## 2 player strategy board game

## “Escape the guards, make your own strategy”

## Written by: Santiago Murillo Londono

### Version: 1.0

### Date: April 25, 2026

## Table of contents
1. **Overview**
  - Theme
  - Setting
  - Genre
2. **Core Gameplay Mechanics**
  - Movement System
  - Guard System 
  - Item System
  - Player Interaction
3. **Target Platforms**
4. **Monetization** 
5. **Project Scope**
  - Game Length
  - Development Time
6. **Influences**
7. **Elevator Pitch**
8. **Project Description**
  - Brief Description
  - Detailed Description
9. **Systems**
  - Turn System
  - Caught State
  - Collision System
  - Trap System 
  - Items decisions
10 **Story and GamePlay**
  - Story
  - Gameplay
11. **Assets needed**
  - 2D Assets
  - Code
12. **Schedule**
  - Phase 1 – Core Systems
  - Phase 2 – Gameplay Systems
  - Phase 3 – UI & Polish
  - Phase 4 – Testing


## Overview

### Theme
The theme of Ninja Escape is being focused on stealth, strategy, luck and calculated risk. The players have a role of being enemies that are trying to escape from a dangerous path while they avoid some guard and implement tramps to interfere in the other player's progress. The game includes some tension between players by making them make constant decisions,and choose between safe or risky movements and when to use their items. 
Rather than keeping the game to rely only on randomness, I make the decision to make the game be more about decision making. The player needs to time their actions, manage their items and adapt to different situations on the board. We included some ninja tools as items like smoke bombs, grappling hooks and having traps to make every move feel intentional. 


### Setting
The game setting is a board with 54 tiles that is arranged similar to the snake and ladders board game. The board has different zones, such as safe zones where players can move freely and place traps, we also have zones where players collect items to escape or put traps, and danger zones that are where the guards move and can get captured. 
We included that guards have some arrow that shows where they are going after so the user has knowledge of guards move and anticipated their movies. We have all items listed as on the left being escaped items and on the right being the traps. We also included a board on the right of the board which has all instructions and information for players. For last we have two buttons for player move where they can choose to move safe or move risky. 

### Genre
The game is a strategy board game with competitive multiplayer mode. The game combines traditional mechanics of board games like rolling and title movement, with modern strategy like managing the items and player movement. The game focuses on luck and skill since it has luck on dice but skill on the decision of when to use the item. 



## Core Gameplay Mechanics

### Movement System
The movement system of the ninjas is based on a dice mechanic where we have two types of dice helping on combining the randomness with the decision making. When a player is gonna start their turn they have to choose between the safe roll that results from dice is (1-4) movement and the risk roll that is of (3-6). This helps to make the player have a choice and have the control of either taking the risk or playing safe depending on the situation. 
After they select which dice, the dice would roll and the player would move forward automatically based on the result. The players cannot skip movement or move backwards unless the item effect allows it. This movement is to change it to be only pure randomness into strategic decisions too.

### Guard System
The guard System is one of the main mechanics of the game. There exist four guards inside the board, each of the guards have their respective path. Their movement is visible where as it exist some arrows show where guard would move next. The gourds move after both player roll their dice. 
Guards move after both players complete their turns. Also, after a third round guard would move twice, this increases the level of danger and forces players to think ahead since it is not that predictable. A player can get caught if they land on the same tile as the guard or if the guard moves onto their tile. If this happens the player can either escape with an escape item or be sent back to the starting tile. 


### Item System
The item system introduces a layer of strategy by allowing players to collect and manage different types of ninja tools. Items are obtained when players land on the specific tiles that are visibly different from regular tiles. Players can choose between two items when they land there so it gives the strategy of what they player needs more at the moment. Each item has an unique effect that can either help the player escape or interfere with the opponent.  Escape items can only be used only when players get caught. Traps can be used anytime the player wants, they can use them before they throw the dice. There exist 4 escape items: smoke bomb (player move back 1 tile to escape), katana (roll 4 and kill guard, if not get caught), Grapple (sent back 3 tiles), dash (move forward 3 tiles) and there exits 3 traps items: Caltrop (opponent land and skip one turn), and tripwire (opponent land and move back 3 tiles).

### Player interaction 
Player interaction is really important in the gameplay. Basically this helps to create a competitive and engaging environment. Players are not only trying to reach the exit but also trying to slow down their opponent. Their interaction mainly happens due to an item system, where players have certain items that can help them escape or place traps for other players. This makes the game not just who is faster but also some type of strategy. 

## Target Platforms
The game is primarily created for a pc and uses the development of a unit game engine to create the game. The game is made to be placed using keyboard and mouse, but mostly mouse since most of the mechanics are used on clicks. The game also is made to work in web platforms mostly using the unity WebGL or the github pages. This is intended to be made to work through a web browser without the installation of anything. The game also has the potential to be made to work in mobile devices, for softwares with iOs and Android. Overall, the platform for now is to work only in PC and web browsers, but since it is only a prototype it has the possibility to expand more in other platforms. 

## Monetization
Ninja Escape is currently designed to be a free gameplay, with no monetization features. The main goal of the game is to complete the project goals that is to demonstrate the mechanics, strategy, design and user interaction. In the future with better mechanics, and better design would be able to have some type of monetization by having upgrades, or character skins. Another option is to have some advertisements to keep the game free but have some type of money from the ads, but for now the game has no monetization. 

## Project Scope

### Game Length
Each match is designed to last approximately between 10 and 15 minutes. The game is created to have a fast pace. Having every match to have a short length helps to keep players' attention and maintain the game with a fast pace. The length can also change in respect to the events during the game like a player being caught by the guards or falling into traps. 

### Development time
The development of the game was completed in approximately three months. This includes the physical prototype, the thinking of the design and the gameplay, the implementation of the core systems and mechanics and every idea of the game. I was more focused on the gameplay mechanics and experience than the design, since I wanted to balance the game to not be with too much randomness and have balance between luck and strategy. 

## Influences
The game of Ninja Escape was inspired by a mix of board games and strategy video games. Games like snake and ladders were an influence on how the board should look like, since the board follows the same design that snake and ladders have. The strategy does not follow a specific game since as now i do not know any game following this specific strategy. And as for using the dice movement it was made to work as any games that use the same dice mechanic. In total this game was meant to be created from zero with respect to playability, and to be something unique or at least most part of the game. 

## Elevator Pitch
Ninja Escape is a fast paced game. The game is for 2 players and is a strategy board game, where each ninja has to find the exit in the 54 board tiles while they avoid guards and traps. In each turn players choose to either play safe that is a dice of (1-4) or play risk that is a dice of (3-6). Players also can collect items around the board, these items can be either to escape or to set up traps. In the game we try to have a combination of controlled risk, randomness, strategic decisions and constant interaction. 

## Project Description

### Brief Description
The game is a 2 player competitive board game design for PC and web platforms. Players take the role of being rivals that have to race across the board and try to be the first one to reach the exit. In each turn, the player chooses between safe or risk dice roll, this allows the player to control their movement. Along the game, the players collect items that can be used to escape or set up traps to slow down their enemy. The game has randomness but also strategic decisions, so players can manage their risk and plan ahead. 

### Detailed Description
The game Ninja escape is a board game that is a 54 tile similar to the snake and ladder board game. The game is two players where both players start at the same tile and have moved across the board to find the exit. The objective of the game is to reach that exit before their rival. At the start of each turn, the player can decide to move between a safe dice roll (1-4) or  risk dice roll (3-6), introducing a strategic decision between safer or faster progression. 
In the game, all guards move in their respective path. After both players roll their dice, all guards move on their path. After three rounds the guards do not move only one title on their path , they move two titles making, this is for players to keep attention and do their strategy. If a player gets caught by a guard, the player can use an escape item to escape from the guard. Players start with one escape card and one trap card, but they can also get more items along the map on specific titles. When they land on an item title they would see two options of items to choose, that helps on strategy since the player gotta decide what is the best for them. 
The game follows a consistent game loop where player one moves, then player two moves, and then guards move. This keeps the game not too difficult to learn and players can focus on other things like strategic decisions. The game balances randomness with strategic decisions. 


## Systems

### Turn System
The turn system consists of specifying the turn of each player. The system works as player one acts and is followed by player two and then all guards move. During each player turn the player chooses between safe roll dice (1-4) or a risk roll dice (3-6). Once both players have completed their turns, the guard phase begins where all guards move on their path one tile or 2 tiles after 3 rounds. There exist some special conditions like skip turns due to a trap, but never break the turn order. The sequence always continues normally. 


### Caught State
The caught state is one of the most important systems in this game. This is for when a player gets caught by a  guard or a trap. If this happens the game gives a decision to respond by using one of the escape items but if the player does not have an escape item and is caught by a guard is sent to the start and if it is a trap can skip their turn or be sent back 3 tiles. 


### Collision System
The collision system is to help the game detect the interactions between player, guards, and traps on the board. The collision occurs when a player occupies the same tile with the guard or a trap. The collision detect these two objects in the same tile and do the right action, is like connecting the player actions with some consequences. 

### Trap System
The trap system allows the player to influence the opponent's progress. Trap items can be placed on the board tiles and remain visible until the opponent lands on it. If the opponent lands on the trap, they would get caught and can escape using an item or accept the trap. Traps can affect player progress by making them lose a turn or move back three tiles. 


### Tile Decisions
The item system gives the chance to make decisions through the game. When a player lands into an item tile, they would be asked to choose between two random items. Thai gives the sense to players to think about strategy and what time might work more for them in that position. Players also have to decide what item to use when they get caught, so if they have multiple items they would need to make a strategic decision of which time might be the best for them to escape. 

## Story and Gameplay

### Story
The game Ninja Escape has a simple story. The game is basically two rival ninjas that are in a dangerous environment where they have to escape and try to avoid the guards and traps. Both ninjas are competing against each other, and only one can reach the exit first and escape from this place. The story focuses on a competitive atmosphere. The idea of escaping gives tension between both ninjas. Players feel pressure to make quick and smart decisions while they avoid getting caught by the guards and traps. The items that are like ninja tools make the story feel more real and players feel like actual ninjas. 

### Gameplay
The gameplay of Ninja Escape is basically a game loop where every round is being repeated. Each player takes a turn where they first choose between safe roll (1-4) and risk roll (3-6), then roll move forward after the throw-in based on the result. The decision is benign, balanced on being safe and having a faster progression. After both players roll their dice, all guards move on their respective path, but after 3 rounds the guards move twice. 
Through the game, the players can take different items on specific tiles. The items are either for escape or place traps to affect their opponent's progress. This creates an interaction between players and makes strategic decisions. The gameplay loop emphasizes planning, timing and risk management. Each turn presents a new decision, every round is unpredictable. The game finishes when one of the players reaches the exit tile. 

## Assets Needed

### 2D Assets
The game requires 2D assets mainly for the board design, player design and user interface. These include the board titles, like the color and structure of each title. The UI elements are also important since we include buttons for rolling the dice, selecting items and interacting with the game. We also have icons for each item to represent each one of the ninja tools. 
We also have game messages or visuals to represent each one of player turns and other visuals so the game can be clear and simpler for the players. We include assets to change the ninjas to be actual ninjas and guards to have a military style. When traps are placed it shows a trap object into the tile. We also include an asset of arrow direction for visual respect on guard movement. 

### Code
The code in Ninja Escape is responsible for managing all the gameplay systems, like the player movement, player turn, guard movement, item usage and collision detection. The game means to use multiple scripts and each script handles a specific part of the system. The game has a flow controlled by a central game manager. This game manager controls the player trunks, dice rolling and most of the game controls. This is to ensure that all the controls work correctly and each action is being performed. 
Player behavior is managed to control all the player movements. Each player has a current position on a title, an inventory of items and status of movement. The controller updates the player position on the board and manages the items by adding or removing the items. The board system uses a title position, where each title has an index to correspond to their position. This allows the character to move consistently on the board. 
The guard movement is handled by specific guard scripts and guard manager. Each guard follows a specific path. The guard manager updates all guards at the end of each round, ensuring that it synchronizes movement between guards. The collision detection system. This system determines when a player is in the same title as a guard. If collision occurs the system forces the player to use an item or if it is not an item player goes back to the start title. 
The item system controls how items are generated, stored and used, Players receive random items, and each item has a specific effect. The system ensures the item is removed after use and that their use works effectively. Each script focuses on specific responsibility, and to help the game work better. 

## Schedule

### Phase 1 -  Core Systems
This phase focuses on building the foundation systems of the game and creating the digital prototype mechanics and systems. The goal was to implement the core mechanics defined before, and ensure all systems work correctly together. During this phase I created the key systems and developed all the movements like player movement, and guards movement, the roll of the dice (risk and safe roll), and the turn management. 
The board layout was also built, with all 54 tiles in their respective positions and set up the start tile, exit tile, the danger zones and the item tiles. The game should follow their gameplay loop by having all these systems and mechanics working correctly. 



### Phase 2 - Gameplay Systems
This phase is focused on adding the main gameplay features to make the game more strategic and engaging. The guard system is also implemented, this includes their path and movement behavior, and that they are able to understand if they collide with players with the same title. Also understand that if the players have an item they are able to let them go, but if it is not an item they caught them and sent the player to the start. We also have the item system where this allows players to collect, store and use items that have different effects. 
Basically in this phase we just create the mechanics that  would allow the players to do certain actions inside the game. 


### Phase 3 - UI & Polish
This phase is focused on improving the visual quality and improving the user experience of the game. We include the buttons, the panel for the inventory, and some panels for information of player turns and messages such as “You use this item” or “ you got caught by the guard”. 
We also include some better visuals with respect to indicators of where the guards are and the icons for the items for players to check what items they have.  The goal is to make the game more immersive and real and increase the user experience. We included all the visual elements like some assets to increase the immersion and have visuals to help players understand the game like instructions on the left and arrow icons to show where guards move. 

### Phase 4 - Testing
This is the final phase of my game development. This phase focuses on testing the game by letting people that haven’t played it before play and then get information and feedback to improve the game. This phase was mainly focused on identifying bugs, and adjusting the gameplay with respect to people's feedback. We had to test all the systems and check everything worked correctly together and the game ran smoothly. We do the respective improvements based on the testing result and people's feedback and adjust the gameplay and improve the game performance.

