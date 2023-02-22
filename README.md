# SpookyGhostGame
![Ghost Game Development](https://d2f8l4t0zpiyim.cloudfront.net/000_clients/1167902/page/cat-ue4-680x300-303282.jpg)

Spooky ghost game is the codename for the development project to create and learn Unreal Engine development.
the basic idea of the game is that up to 4 players are being hunted by a ghost in some environment (School, Hospital, etc) and have to escape while the ghost hunts them
Players win by finding clues about the ghost and using the clues to weaken the ghost and unlock the ability to escape.

**Currently, the game's ghost AI has been fully implemented and has the following features:**
1. Wanders the map in specific "areas of interest"
2. has a boredom level which allows the ghost to choose when to interact with objects, make spooky noises, or find a new area of interest
3. After enough time has passed, the ghost will hunt the players. it does so by listening to sound they are making (through walking, interactions or talking on mic)
4. Ghost has the ability to see players aswell and can use this to hunt them. Creates a 'last known location' marker for each player and attempts to find players in the last known area.
5. Can check hiding places like lockers, under beds, or in rooms with closed doors.
6. After being unsuccessful in hunting, will revert back to explore more.

As the game is well over 50GB in development files, its impossible to host on GitHub, but demonstration of the game can be shown over call.
