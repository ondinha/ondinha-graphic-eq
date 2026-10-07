# Ondinha Graphic EQ

**10-band octave graphic EQ with analog-matched bells (31 Hz - 16 kHz, +-12 dB). Broad, musical tone shaping for buses and masters.**

A VST3 and Audio Unit plug-in from [Ondinha](https://github.com/ondinha), a DAW 2.0: native AI tools combined with traditional sound engineering tools.

Ten sliders, one octave each, from 31 Hz to 16 kHz. For broad tone moves on a bus or a master, where a few gentle dB matter more than surgical filters.

The bells are matched to analog curves, so the top octave behaves like it should and doesn't cramp near the top of the spectrum.

## What it's good for

- Final tilt on a master: a dB of air, a dB less mud.
- Quick tone on a bus or a reverb return.
- Matching tone to a reference track (its bands map cleanly onto a 1/1-octave analysis).

## Controls

| Control | Range | What it does |
|---|---|---|
| 31 Hz ... 16 kHz | +-12 dB | Ten one-octave bells. |
| Output | +-12 dB |  |

## Download and install

Builds will be on the [Releases](../../releases) page.

**macOS:** copy `Ondinha Graphic EQ.vst3` to `~/Library/Audio/Plug-Ins/VST3` and `Ondinha Graphic EQ.component` to `~/Library/Audio/Plug-Ins/Components`, then rescan plug-ins in your DAW.

| Format | Platform |
|---|---|
| VST3 | macOS |
| Audio Unit (AU) | macOS |

Works in any VST3 or AU host: Ableton Live, Logic Pro, Reaper, Bitwig Studio, Cubase, Studio One, FL Studio and others.

## How it works

Analog-matched one-octave bells. Moves glide (~20 ms), a flat band costs nothing, zero latency.

## More Ondinha plug-ins

- [Ondinha Bus Comp](https://github.com/ondinha/ondinha-bus-comp): Console-style glue compressor for the mix bus and groups.
- [Ondinha Split EQ](https://github.com/ondinha/ondinha-split-eq): Transient / tonal split EQ: separate gain for the attack and the sustain in every band.
- [Ondinha Limiter](https://github.com/ondinha/ondinha-limiter): True-peak brickwall limiter for mastering, with an optional oversampled clipper.
- [Ondinha Unmask](https://github.com/ondinha/ondinha-unmask): Spectral side-chain ducking: dips a track only at the frequencies where the key is loud, only while it plays.
- [Ondinha Resonance](https://github.com/ondinha/ondinha-resonance): Dynamic resonance tamer for harsh mixes, vocals and guitars: pulls down narrow peaks only while they ring and leaves the broad tone alone.
- [Ondinha Imager](https://github.com/ondinha/ondinha-imager): Multiband stereo imager with mono low end: width for lows, mids and highs on phase-matched Linkwitz-Riley crossovers.
- [Ondinha Delay](https://github.com/ondinha/ondinha-delay): Tempo-synced stereo / ping-pong delay with filtered, saturated feedback and ducking, so the echoes stay out of the way of the vocal.
- [Ondinha Tube Air](https://github.com/ondinha/ondinha-tube-air): High-frequency exciter with a tube stage: adds warm even or bright odd harmonics above a frequency, under the untouched signal.

## Feedback

Found a bug or a host where it misbehaves? [Open an issue](../../issues) with your DAW, its version and your OS.
