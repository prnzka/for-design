# For design

Dialogue audio for a 41-second vertical animated short, "The Side Door".
Two characters, 16 lines. Everything here is final as rendered and ready to cut
against picture.

**`dialogue-stem-41s.wav`** is the whole thing already assembled at the cue
times below: 41.0s, 48 kHz mono, no overlapping lines. If you just want to drop
one file under the animation, use that. The individual takes in `audio/` are
there for retiming single lines.

## Cues

Start times are from the top of the film. MAX is the hard ceiling for each line:
13 of the 16 sit flush against the next cue, so a line running over its MAX
collides with the following one.

| Cue | File | Who | Line | Start | Length | Max |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | ow01 | Owner | "I've got a website. Nobody calls." | 0:00.0 | 2.36s | 3.0s |
| 2 | kb01 | K-Bot | "I've been at the Hale door all morning." | 0:03.0 | 1.76s | 4.0s |
| 3 | kb02 | K-Bot | "So have those three." | 0:07.0 | 1.29s | 2.0s |
| 4 | ow02 | Owner | "It's open." | 0:09.0 | 0.96s | 1.0s |
| 5 | kb03 | K-Bot | "All pictures. Not one word." | 0:10.0 | 1.65s | 2.5s |
| 6 | kb04 | K-Bot | "Nothing on Hale dot com says what you sell." | 0:12.5 | 2.37s | 4.0s |
| 7 | kb05 | K-Bot | "And the side door's latched." | 0:16.5 | 1.58s | 2.4s |
| 8 | ow03 | Owner | "I did that. It blocks bots." | 0:19.0 | 2.19s | 3.0s |
| 9 | kb06 | K-Bot | "It blocks Hale out of the answers." | 0:22.0 | 1.87s | 3.5s |
| 10 | kb07 | K-Bot | "Real words." | 0:25.5 | 0.98s | 1.4s |
| 11 | kb08 | K-Bot | "Say what you sell." | 0:27.0 | 0.97s | 1.0s |
| 12 | kb09 | K-Bot | "Unlatch it." | 0:28.0 | 0.93s | 1.5s |
| 13 | kb10 | K-Bot | "Now I can tell people what you do." | 0:29.5 | 1.81s | 4.0s |
| 14 | kb11 | K-Bot | "We're Kodigoes. It's all written down." | 0:33.5 | 2.16s | 3.0s |
| 15 | kb12 | K-Bot | "Comment site." | 0:36.5 | 0.93s | 1.0s |
| 16 | kb13 | K-Bot | "We'll apply this to your website." | 0:37.5 | 1.66s | 3.4s |

Spoken dialogue totals about 23s inside a 41s film, so roughly 18s is silence.
That space is intentional: the piece plays dry and understated.

## The two voices

- **Owner**: a middle-aged small-business owner. Low, quiet, worn out. 3 lines.
- **K-Bot**: a small robot who reads websites. Deliberately flat and even, and
  band-limited so he sounds like he is speaking through a small built-in
  speaker. 13 lines.

The two sit about 4.6 semitones apart in pitch, so they never blur together.
In cue 14, "Kodigoes" is pronounced KOH-dee-gohs, like "code".

These are synthesised voices rendered locally, not recordings of human
performers. They are not directable for emotion, so the performance is carried
by pacing and by the edit.

## Format

Every file: WAV, 48000 Hz, 16-bit, mono. Loudness about -16 LUFS integrated
with true peaks below -1 dBTP, matched across all 16 so no line jumps out. Dry:
no music, no effects beyond K-Bot's speaker treatment, and no reverb, so reverb
and room can be added to taste. Speech starts within 0.05s of each file's start
with roughly a 0.1s tail.
