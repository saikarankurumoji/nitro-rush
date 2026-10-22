# Nitro Rush 3D: GitHub Pages version (no server, no Node)

1. Create a GitHub repo and upload `index.html` (Add file > Upload files).
2. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
3. After a minute your game is at https://YOURNAME.github.io/REPONAME/ . Share that link.

Multiplayer: one player clicks HOST ROOM and shares the code. Friends click JOIN.
It uses WebRTC (PeerJS) so players connect directly; the host's browser relays the game.
The host must keep the game tab open and in front. Up to 8 players.
