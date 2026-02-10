Adding scroll bar behaviour in the desklet app.

Modification of Cinnamon desklet Note by schorschii. Added word-wrap + parameter for better word-wrap fit (word-wrap font scale factor)
Replace desklet.js and settings-schema.json in ~/.local/share/cinnamon/desklets/notes@schorschii and restart Cinnamon or log-out + log-in.
word-wrap functionality is cloned from aizma from repo: https://github.com/aizma/Note-by-schorschii---word-wrap#

Clone the repo and run the below commands to load the updated desklet app in Linux mint:

    cp Note-by-schorschii---adding-scrollbar/desklet.js ~/.local/share/cinnamon/desklets/notes@schorschii/desklet.js

Restart Cinnamon to make changes effective using: ALT + F2, type "r" and press enter.
