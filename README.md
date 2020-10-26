# bfg-lfo
a 1d modulation source build using max/msp/jitter's jit.bfg object

this is basically just a regular old LFO that uses a signal derived from basis functions instead of a standard periodic waveform like sine or a triangle.

the result is a whole variety of undulating signals that are not totally random (like noise) but also not totally predictable (like sines, triangles, etc)

for more info on basis functions, see daniel shiffman's fantastic [tutorials](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6bgPNQAdxQZpJuJCjeOr7VD)on Perlin noise!

## the files
* **bfg-lfo.maxpat** main patch that you can use as a bpatcher. outputs two modulation signals
* **bfg-lfo.amxd** max for live version
