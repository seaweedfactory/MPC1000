# Templates for the Akai MPC1000

This repository contains template files for the Akai MPC1000.

KEYMAP3.PGM:
This is a program file which contains a basic chromatic key mapping. The free version of JJOS is required for using this file. Use the following steps to set this mapping up for any sample and root note.

JJOS saves some time by providing a global edit mode, accessed by pressing MODE then PAD 11. Move the cursor into the sample box. Press WHOLE to select all pads in the program. Select the sample you wish to use. It should has the same root note chosen above, in this case middle c. Different octaves of the root note can be used and the tuning will still be accurate. There is a limitation in that the sample cannot be tuned to the root note in the program. I would suggest creating a new program, shifting the tuning of the note to the desired root note and resampling using the MAIN OUT option in RECORD mode. After selecting the proper note, press WHOLE again to leave WHOLE mode. You will not hear any sound if you send MIDI notes to the MPC in global edit mode while WHOLE is active.

You must set the envelope of each sample individually. However, pressing another pad allows adjustment of settings for that pad from within the same window. Also, you can set different envelopes for each sample. This is useful if you would like high-pitched sounds to decay faster, as many real instruments exhibit this behavior. The decay setting is important as it will allow the sound to fade out when a key is released.

Sometimes we want a sound to sustain as long as we hold down a key. To achieve this, we must use the looping feature. To do so, go to TRIM mode and select the sample used for the root note. Select the START TIME box and press WINDOW. Choose Loop point=Start Point:NO. This will start the loop at another point within the sample instead of at the beginning. CLOSE this window. Press LOOP to activate loop mode editing. Turn the loop mode on the changing the OFF next to the sample name to ON. The start time box changed to the loop point box when we entered edit mode. It is labeled Lp. Use this to select when the same should start looping. The end point selects the end of the loop. Everything after the loop point will not be played; instead the sample will loop as it fades out. Use the JOINT mode to reduce the click where the loop ends meet. My preferred method is to start and end the loop at zero volume. Go to global edit mode again by pressing MODE then PAD 11. The play mode must be set to NOTE ON to use the looping feature. Make sure it is set correctly.


