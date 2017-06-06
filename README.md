# Pau Olive Rubio - Ice Crew's Designer  
  ![](http://imgur.com/a/z9S4q.png)
Personal involvment into IceCrew's 'TLOZ:A Dream to the Past' tribute game.  

- ## Entity System  
  The 'Entity System' is what we called all the methods, classes and other aspects of the code that involved the 'entityManager' to work.  
  These covers almost every element you can see inside the game and can be interacted with.
  - ### Enemies & AI  
    Enemies were one of the most complex entities to implement. They requiered a lot of design iteration, testing and balance.
    As the designer, I used the choosen designs to create the enemies you can see inside the game, this meant the creation of AIs for each one of them and different patterns to estimulate player's fun.  
    Also the Agahnim Boss enters in this category which was one of the toughest challenges.
  - ### Item System  
    Items play a great role inside the game mechanics, player can buy them or pick it from the scenes to upgrade their stats or change in some way.
    Each one counts with a description an GUI appearences on the inventory.
      - Reward System   
        Basically, this is a simple reward system based on probabilities that change between enemies (rupees, hearts, potions, ...).
      - Weapon System (NOT IN THE FINAL GAME)
        This was meant to be in the game but had to be cut off due to time issues.  
        The weapon system, as it was when cut off, had two different weapons: Sword and Bow, which you could change between if you had them. they were droped as Items and were a way to upgrade the player outside the stats changes.
  - ### Doorway System  
    Doorways are simple doors that open or close depending on the amount of enemies in the room. They are used to change between rooms (including animations).
- ## File Acces System (w/ Pau Bonet)  
  Basically all file access done inside the game. I worked mostly on the save and load system.
- ## Controller Support (w/ Pau Bonet)  
  Designed all the controls and presets for the controller and implemented them.
- ## Player  
  - ### Movement / Attack
    Includes collisions and attacking interactions with enemies.
    Note: The 'Attack' included the cut off Weapon Support (T.T)
  - ### Dash  
    The Dash mechanic was implemented aftersome tests. We saw some more action was needed so this acted as a way to avoid damage and to improves player skill sensation. 
  
- ## Projectile / Particle System  
  Projectiles and particles act in a similar way but projectiles actually interact with the player and the entities.  
  
- ## Scenes & Rooms System  
  Basically, improved Scenes (including the implementation of the 'Arena Mode') and a Room System that encapsulated logic to just the current room.  
  
- ## Video Player  

- ## Others  
  - ### FX/SFX (w/ Roger)
  - ### Game Art (w/ Jan & Roger)
  - ### Ordering Sprites  
  - ### Camera Culling  
  - ### Debugging  
  - ### Helping Team Mates  
  - ### ...  
  
- ## Lead Designer (a.k.a 'The Friendly Dictator')
  As the Lead Designer I managed the team in order to have a lot of design to choose from. We went into design sprints as well as we were going for code sprints to ensure good design inside the game.  
  Needles to say, I acted as the main filter.  
  Once in the production phase, I also was in charge to cut off those design that weren't posible to implement on time or resources.
