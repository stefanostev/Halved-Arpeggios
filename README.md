# Halved-Arpeggios

Max For Live MIDI 8-step sequencer aimed to light up inspiration.

Half of the notes are inputted by the user, the patch creates the remaining half. 

The user can input up to four simultaneous notes, that are spread over the first four steps of the sequence. In order to do so, the notes must be pressed and hold at the same time, like the usual procedure for arpeggiators. Any note added beyond the fourth one will be spread starting from step 1 to 4 again (i.e. notes 5-6 are going to replace notes 1-2). In the current version, generated notes are based on relative one-octave major scale of the correspondent input note (note value in step 1 will be the root note of the major scale from which the patch will create the note for step 5, note value in step 2 for step 6, and so on...). The small toggles near the note indicator turn on/off the correspondent step. The user can also change notes manually by dragging the mouse up and down on the desired value.

The RNDM NOTES section controls generated notes. User can de-activate constant refresh of notes generation by turning off the white toggles relative to single steps: by doing so, the note will refresh only when a new note will be inputted in the other half correspondent step. Switching on the ADD/SUB toggle will generate notes in a mirrored major progression in the lower octave.

PLAY runs the sequence, RESET resets it to the first step.

The sequencer has a tempo division menu. By activating AUTO, divisions will change randomly.

SWING controls the sequencer swing, STEPS sets the total length of the sequence, DUR controls the duration of notes gate.
