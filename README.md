# circuitbender
Novation Circuit hacks

## Todo
-v Use number instead of name in for synth in parameters (default control synth), and one array that maps number to name
-v use mappings when updating midi mapper table
-v support drum panning, channel
-v settings gui hookup
- learn buttons
- style buttons
- test with 2 circuits
- remove use of macroControls
- don't pan to extremes, because Circuit bugs out and includes some in the other ear as well
- pass mappings as parameter to functions, and settings, and get rid of other uses of global variables
- optimize receiveMIDIMessage
- javascript in separate file
- create utility class for the non-gui stuff, perhaps