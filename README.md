# Progression Ear Trainer

A small web app for guitar ear training, built to use on a phone.

- **Chord progressions:** hear four chords in a real key, see the first chord, and pick the right progression from four options (chord names and Roman-numeral degrees).
- **Chord quality:** hear one chord, name its type (major, minor, 7, maj7, dim, 9, 11, 13 and more), then see the guitar shape.
- Rounds of 10 questions, with guitar, piano or lo-fi keys sound.
- Score history with dates, a progress chart and your hardest progressions or chord types.

Everything is in `index.html`. Sound is synthesized in the browser with the Web Audio API.
History is saved in the browser's local storage, so it stays on the device and browser you use.
