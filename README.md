
I thought long and hard about how to make a clock divider sound cool.

I gave up.

This is the successor to my original divider module (and it's short-lived 1U counterpart) but is slightly different in that it now has divisions down to /64 - that's it. For best results, use a trigger voltage of around 5-6V (more is better, within reason) although anything above around 2V will work. At audio frequencies you could even use it as a sub-octave generator, and feeding individual outputs into a R2R DAC can yield some interesting sounds.

Note that the divider will trigger on the *falling* edge of a clock pulse - this is a 'feature' of the 4040 IC on the board; you can get around this by either using an 'inverted' clock input to the divider or using the divided signal as a 'master' clock source.

Exciting, eh? Nothing to see here, move along.

**THIS IS A COMBINED THROUGH-HOLE/SURFACE MOUNT PCB** - this means that there is a mixture of surface mount (0805/SOIC) and through-hole components. Whilst it isn't an ideal beginner's board, if you feel confident hand-soldering SMD components then the build is straightforward enough.
