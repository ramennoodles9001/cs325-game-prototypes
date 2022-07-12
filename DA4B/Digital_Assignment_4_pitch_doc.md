# My Generic Fantasy
* **Originality:** What is original about your game?
  MFG is an RPG with fun dynamic combat and a world to explore.

* **Technical Merit:** What is interesting about your game technology?
  MFG is made in Unity and one of the interesting aspects of the technology is the implementation of a Finite State Machine for Enemy AI. In my previous project this state machine was extremely simple and didn't respond to the environment. This updated version is much more flexible and responds directly to the environment. Also the use of Collider layers allows the project to have hidden areas to explore.

* **Prototype Postmortem:** What did you learn from this prototype? What was the easiest or hardest part of making it?
  As my project grew in complexity, one of the most complicated aspects was how colliders where implemented. For example, creating a collision for a sign which would display text inadvertently blocked certain attacks due to the attack hitting the sign and then not following through to the enemy. Another difficult portion was getting timing correct with enemy animations and states. Some of the easier parts was the map building. Creating colliders and hidden colliders proved to be simple due to Unity's tile map system. UI was also relatively simple to implement but something I expect to get harder as I polish this project.

* **Prototype Assets:** Did you make your prototype assets from scratch? Did you borrow them? Cite your sources here.
  I borrow the player and enemy assets as well as an environment asset pack. This sums up to be all the art work in the game.
  https://assetstore.unity.com/packages/2d/characters/hero-knight-pixel-art-165188
  https://assetstore.unity.com/packages/2d/characters/bandits-pixel-art-104130

  https://oddpotatogift.itch.io/16x16-fantasy-pack?download

* **Prototype Closest Other Game:** Which other game most closely resembles your game? If you are borrowing code from a Phaser Example, you must say so here. If you borrow code from elsewhere, you must say so here.

  The game most similar is salt and sanctuary/dark souls. I borrowed a little bit of code from the hero knight asset packs but most of it was commented out or deleted because they did not fit my needs. The code that came with the asset packs was basic movement for the hero knight but most of it is heavily modified. The only code used in the bandit asset pack was ground detection which is just a few lines of code, everything else is commented out.

* **High Concept:** A one-sentence summary of your game.
  Explore a world full of surprises and fight off powerful foes.

* **Theme:** State which of the themes or challenges you used.
  None

* **Mandated Variety:** State which input, randomness, genre, and play style you used in this prototype.
  Input is mouse and keyboard, Randomness is mostly deterministic, playstyle is explorer and achiever. Genre is adventure platofrmer and rpg. 

* **Prototype Goal:** What game mechanic is this prototype evaluating?
  The prototype is evaluating the combat of the game, platforming, and a simple quest system.

* **Player Experience Goals:** What experience do you want players to have when playing your game?
  I want players to be able to have the freedom to do what they want but with obstacles they must overcome.

* **Gameplay:** A paragraph describing the actions the player can perform, the system dynamics, and the core mechanic. Include a concise explanation of the prototype’s inputs and their expected effects (how to play). You can also describe game play that is not in the prototype. You may include mock-up images for parts of the game not in the prototype.
  The game allows for multiple approaches to combat with a stamina system. The player may attack, roll, block, or jump. Rolling grants invincibility for a moment while blocking stops attacks from in front of you. Both of which drain stamina. The enemy has an AI system which has 3 major states. Idle, Patrolling, and Chasing. During Idle the enemy will stand few a set amount of time and then turn around. Patrolling will move the enemy for a certain amount of time or until they hit a wall or ledge. Chasing occurs once the player gets close enough to the enemy. They will actively jump to get to the player and attack them. 

* **Strategies:** What player strategies do you expect will be effective at playing this game?
  I think that a lot of dodging can happen in the game by simply running past enemies or back up after they attack.

* **Story/Setting/Premise:** A paragraph about the world your game is set in and who the characters are. What makes the game world and its occupants unique and interesting? Do the tokens represent something? If the game has a backstory, mention it here. If the game is abstract, then say so. How will the dramatic tension interact with the gameplay tension?
  You are a lone knight who is exploring a forgotten world to find the mysteries of the past. The story will be told in quests and lore and such will be slowly discovered through gameplay.

* **Target Audience:** A single sentence that describes the demographic you're trying to reach.
  I am reaching for the RPG demographic.

* **Play Time:** How long does your game take to play?
A few minutes for now. For someone who has never seen it I expect a playtime of 5 minutes for the prototype.