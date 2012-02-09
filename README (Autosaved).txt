This is an interface to the BCF2000, according to the patch included. Not smart, I know, but my first MIDI patch, and I don't want to start over again :P

How it works: 

Console consists of 8 channels, corresponding to each channel on the BCF. Each channel returns a list, composed of the following elements, in order:
1. channel #
2. Lock/unlock (0 / 127)
3. Mute/Demute (0 / 127)
4. Fader
5. 
