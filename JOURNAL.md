# Journal

#### 7/10/2025

I've decided to make a mini rhythm game that goes on a keychain and that you can play on the go, hence the name DD-Go! Today's a day of brainstorming and planning. First of all, I want to outline the general algorithm of the game and what it should end up having.

Ideally, I'd want this:
1. Start Screen
2. Song Selection Menu
    - When hovering a song, it plays a preview of it, and then displays the high score
3. The Game
    - 4 arrows to press
    - Scoring System
        - You'll score these on notes: Perfect, Good, Ok, Miss
    - End of Song Screen
        - Displays score, high score, and number of Perfects, Goods, Oks, and Misses

However, that is a lot of features and is something a little more complex. Considering I want to pack this game onto a tiny keychain and that I'll be using an ESP32 microcontroller, I think I'll simplify it to:
1. The Game (more of a visual game, no audio/limited audio)
    - 4 arrows to press
    - Scoring system
        - You'll score these on notes: Perfect, Good, Ok, Miss
    - End of Song Screen
        - Displays score and high score

I think I'll pursue that more complex project another time with a raspberry pi maybe. For now, I want to keep it simple. I'm also going to be trying PCB design for the first time and then I'll be trying to push the boundaries of my amateur 3D modeling skills by making a case for it...

I've been looking for several resources on where to start. I think I'll be using MicroPython or CircuitPython for this project, and will look into libraries I can use to help me with the game. [Hack Club's Hackapet](https://hackapet.hackclub.com/) program is very similar to this and I think I'll be able to use it as a really great reference for what I'm making. They had their own PCB and shipped it to students, while I'll be making my own and getting my own parts for this project. The code setup is really what I'm going to draw from it.

#### 7/23/2025

Unfortunately... I was caught up on life and got busy doing other things 😢 I wanted to finish this project by the time school started for me (early August), so I was thinking of scrapping the hardware part and instead just creating this game as something on your desktop or as a chrome extension,which still encapsulates the "GO" part of the name DD-Go.

I'm thinking of, if it were to be a chrome extension, just a mini pop-up. There'd be a few songs, and I'd try to keep the 4-note setup.

Now, I'm still planning things, and I'm going to start working on the mechanics soon! I'll be looking into how to create chrome extensions and stuff. I was thinking about starting to create the sprites and art soon, but I've recently learned that it is probably important to "greybox" and work on the mechanics before adding details and other things.