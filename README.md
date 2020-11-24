# FM Synthesizer
Exploring Frequency Modulation Synthesis in Pure Data

## Intro
This Pure Data project features 4 FM instruments: Brass, Clarinet, Plastic Drum
and Ghost. By manipulating and maintaining *carrier* and *modulation*
frequency relationships, controlling an *index of modulation* for
modulation amplitude, as well as different amplitude envelopes for each note, we can
control the presence of harmonic overtones, thus using 
different timbres and effects to create synthesetic instruments.

**Brass**
- Fundamental Frequency: f<sub>0<sub/>
- Carrier Frequency: f<sub>0<sub/>
- Modulation Frequency: f<sub>0<sub/>
- Modulation Index: 5
- ASR: 100 800 100 (ms)

**Clarinet**
- Fundamental Frequency: f<sub>0<sub/>
- Carrier Frequency: 3f<sub>0<sub/>
- Modulation Frequency: 2f<sub>0<sub/>
- Modulation Index: 3
- ASR: 100 800 100 (ms)

**Plastic Drum** 
- Fundamental Frequency: f<sub>0<sub/>
- Carrier Frequency: f<sub>0<sub/>
- Modulation Frequency: 5
- Modulation Index: 2
- ASR: 1 1 100 (ms)

**Ghost** (Exponential Decay Envelope)
- Fundamental Frequency: f<sub>0<sub/>
- Carrier Frequency: f<sub>0<sub/>
- Modulation Frequency: 5
- Modulation Index: 2
- ASR: 200 700 500* (ms)
  
* - Exponential Decay Envelope with according to the [T60](https://ccrma.stanford.edu/~jos/st/Audio_Decay_Time_T60.html)

## Setup

1. Download and install [Pure Data](https://github.com/pure-data/pure-data)

2. Open [./A5](./A5)



