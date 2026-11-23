# Embedded audio production

No TTS is used.

For each approved episode, produce one mastered MP3 per language and embed it in `app/src/main/res/raw`.

Recommended master workflow:
- Female human narration or a voice with explicit commercial synthesis rights.
- Record/edit master at 48 kHz / 24-bit WAV.
- Keep background score subtle under narration; duck it further during Sanskrit verses and important names.
- Export mobile delivery MP3/AAC around 64-96 kbps mono for speech-heavy episodes.
- Normalize consistently across every episode and test with phone speaker, Bluetooth earbuds, and car audio.
- Music must be original, commissioned, or commercially licensed for redistribution inside an Android app.

File names use lowercase ASCII only, e.g. `bk01_te.mp3`, `bk01_hi.mp3`, `bk01_en.mp3`.
