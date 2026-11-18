# practice-player
Metronome and drum machine for guitar practice, embeddable in Notion

## Tab player (`/tabs/`)

Guitar Pro tab player built on [alphaTab](https://alphatab.net): cursor, playback, speed, section and bar looping.
Open https://skl83.github.io/practice-player/tabs/?song=blue

- Add a song: put the `.gp`/`.gpx`/`.gp5` file in `tabs/songs/` and add `{"id", "title", "file"}` to `tabs/songs/songs.json`.
- Any file can also be opened from the device or dropped onto the page.
- URL options: `song`, `file` (URL), `track` (1-based), `section` (name start, e.g. `solo`), `bars=3-6`, `loop=1`, `speed` (percent), `view=tab|score`, `layout=horizontal`, `scale`, `metronome=1`, `countin=1`.
