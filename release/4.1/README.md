### v4.1 Follow-up Notes

Version 4.1 had some great improvements on v4.0. Some of the most notable improvements were a dedicated circuit board, use of heat-set brass threaded inserts, and the centering of the TV. Here are some notes that could be useful for improvements in the next version.

#### Electrical Assembly

Version 4.1 differed from 4.0 by introducing the first integrated circuit board that was done specifically for this project. This was a very simple circuit as it only included an audio routing section, a transformer to isolate the audio input from the television and a passive resistor network to sum the TV channels to mono. It greatly reduced assembly time by using molex connectors and reduced the amount of internal cabling needed to properly route all of the signals. Considerations for next steps would be the addition of a onboard microphone preamp and onboard audio amplifier so that all electronics are self contained. At this point the only connections would be to the panel.

#### Physical Assembly

One of the most difficult things about this version is the physical assembly of the unit. We are currently using 3D printed parts in PETG with heat-set brass inserts. So far we have been quite happy with the mechanical durability with this process but the assembly of all of the parts continues to be prone to error. Below are some considerations for a future version that would increase the precision of the assembly and also reduce the amount of time required

1. Combine printed parts into one single 'insert' that can fit directly into the pelican case.

   - Positives

     - Able to have precise measurements
     - No need to use clamps while epoxying the insert
     - Better durability from one piece
     - Better adhesion from increased surface area
     - Faster assembly

   - Negatives

     - Need to precisely model interior of pelican case
     - Subject to change if case undergoes design changes
     - More difficult to print a single piece of this size
     - Uses more material to print

   Overall I think the positives outweigh the negatives. With a single piece printed piece we could easily apply epoxy without the need for tools or special equipment and simply position the insert into place. With the brass threaded inserts this provides a very quick and easy way to get repeatably good results.

2. Change power switch labeling for on/off vertical alignment

   - Positives

     - More Clear

3. Use a detachable speaker cable

   - Positives

     - Less Tangle
     - Easier to put away

   - Negatives

     - Another jack on the electrical panel
     - Another possible point of failure
