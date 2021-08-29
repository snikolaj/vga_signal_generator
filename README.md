# vga_signal_generator
VGA signal generator based on a Ben Eater design, much improved with GALs. The GALs are used to replace a total of 14 chips. It fits on just 1.5 breadboards.

It works with a 10MHz clock (200 horizontal pixels), but it can very easily be extended to work with 20MHz (400 horizontal pixels). 

It's theoretically possible to include the last horizontal and vertical counter on the GALs, and then add 2 more GALs to replace the other counters.
