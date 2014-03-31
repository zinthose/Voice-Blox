Voice-Blox
==========

## Development Stage:  Planning

## About
This is my attempt to adding voice chat support to Minecraft.  I'm going to _TRY_ and implment support for Teamspeak and/or Mumble. 

### TODO

- Plan Features
- Determine if Teamspeak and Mumble can be implemented in Java and is viable for implementation. 

### Planned Features
- Teamspeak Support
- Mumble Support
- Spacial Support:
  - Allow for playback of user speech based on the spatial coordinats of the player in the game.  AKA is the player within "earshot" of the speaking one?
  - Facing direction will also affect volume levels based on a cone.
  - Whisper mode: If the speaking player is Sneeking, then they will use a Whisper mode allowing for only players within 2 blocks of the front of the user to hear.
  - Mobs can react to noises.
    - Examples:
      - Mobs might investigate an area they heard a sound even if they can't see the player.
      - An angery wolf might be soothed with a calming "shhooshing" sound.
- Ability to warn / autoban playeres based on sustained sound levels.
  - People playing music for example can get anoying when transmitting globaly across the server.
- White/Blank/Mute Lists for both client and server side.
- API Layer for additional mod support.
  - Speech Recognition able to trigger redstone/comand blocks/or other mods.
- Speech Recognition
  - Some basic commands added to the game
    - Examples:
      - "Sick`Em!" - Send all Tamed wolf with in earshot to attack the target you are looking at.
				- "Here Kitty Kitty" - Call your cats within earshot.
				- "Sit!" - Will pacify an angry tamed dog that belonges to the speaker.  And of course, he/she will also sit.  ^u^
  - Talking to plants help them grow a little faster.
  - Chat Modes: Survival, Chat Room, and Mixed.
    - Survival: 3D spacial mode were players can only hear the other players nearby. This mode allows for different push to talk options, Whisper, Normal, & Yelling.  Global chat is available to OP'ed players and those white listed.
    - Chat Room: Nothign to special, just a in game TeamSpeak client UI without the spacial support.
    - Mixed: A hybrid of the Chat Room and Survival.  Basically give everyoen access to Global.
