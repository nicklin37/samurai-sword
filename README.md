# Samurai Sword Display Game

This repo is an online multiplayer Samurai Sword viewer (for all legal intents and purposes)

Game rules found [here](https://www.ultraboardgames.com/samurai-sword/game-rules.php)

Game Design:

                                    |-------------------------|
                                    |       Game Class        |
                                    |-------------------------|
                                                |
                                                |
                                                |
                            -----------------------------------------------
                            |                                             |
                            |                                             |
                |---------------------------|                 |--------------------------|
    ------------|       Player Class        |                 |         Deck Class       |
    |           |---------------------------|                 |--------------------------|
    |                       |                                             |
    |                       |                                             |
    |               --------------------                        |----------------------|
    |               |                  |                        |      Card Class      |
    |               |                  |                        |----------------------|
    |       |---------------|   |-----------------|                       |
    |       |   Role Class  |   | Character Class |                       |
    |       |---------------|   |-----------------|                       |
    |               |                  |               -----------------------------------------      
    |               |         ----------                |                 |                     |
    |               |         |                         |                 |                     |
    |    ------------         |         |------------------|      |------------------|    |--------------------|
    |    |                    |         | WeaponCard Class |      | ActionCard Class |    | PropertyCard Class |
    | (Honor Points)(Resilience Points) |------------------|      |------------------|    |--------------------|
    |    |                    |
    |--------------------------