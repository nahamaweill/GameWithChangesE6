# Unity week 2: Prefabs, triggers, coroutines

## Credits

Online courses:
* [The Ultimate Guide to Game Development with Unity 2019](https://www.udemy.com/the-ultimate-guide-to-game-development-with-unity/), by Jonathan Weinberger

Graphics:
* [Matt Whitehead](https://ccsearch.creativecommons.org/photos/7fd4a37b-8d1a-4d4c-80a2-4ca4a3839941)
* [Kenney's space kit](https://kenney.nl/assets/space-kit)
* [Ductman's 2D Animated Spacehips](https://assetstore.unity.com/packages/2d/characters/2d-animated-spaceships-96852)
* [Franc from the Noun Project](https://commons.wikimedia.org/w/index.php?curid=64661575)


## New changes in the game

Change 1: The player start the game with 3 lives. He can see the number of lives left in the right corner of the screen.
Every time the enemy hits the player, the player loses a life.
Code: GameWithChangesE6/Assets/Scripts/3-collisions/DestroyOnTrigger2D.cs
GameWithChangesE6/Assets/Scripts/4-text/LifeScore.cs

Change 2: There is a new bonus in the game, Whene the player collect a 'L' he gets 1 life.
Code: GameWithChangesE6/Assets/Scripts/3-collisions/MoreLife.cs
