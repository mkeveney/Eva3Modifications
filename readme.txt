8/14/2024

I just finished upgrading my RatRig, and have made a few EVA 3 modifications.  It was designed in the following Onshape document, which was copied from the EVA page.  I've also copied the mesh files to Github, Thingiverse, and Printables.

https://cad.onshape.com/documents/b351c67621eaae69eba7c628/w/d4ddc1c1f22996a018bcad89/e/
780d6d940259a333f0b77ea6?renderMode=0&uiState=66bcf11a1674cf444f03e218

Eva project home page: https://main.eva-3d.page/

The contributions are:

    Alternate Tri-horn fan duct with mount for Beacon scanner.

        My beacon is a D type, and has been assembled in 'low profile' fashion with _NO_ connector.  I soldered the wires directly to the circuit board to save space.  When I got my Beacon (about a year ago) I contacted Beacon support to request a disassembled board.  They suggested instead that I let them assemble it for me in this low-profile configuration, but without the connector.  This enabled them to complete a testing or calibration step or something.  I'm not sure what their current practice is so contact them and ask.  I'm also not sure this will fit the new H style Beacon, but I suspect the mount holes are the same.

        The mounting cavities in the shroud are sized for M2.5 nuts (5mm across flats).  I found that flat-head M2.5 screws still fit and have a very low-profile that should minimize chances of hitting the bed, ...though this was probably overkill.

        I had to slightly change the path of the central duct to make room for the Beacon.  I think the air flow should still be very similar.

    Mount for Nitehawk 36 toolboard, compatible with Orbiter 2 mount.

        I believe this will also fit the BTT EBB36 toolboard.  It has two holes which align with the Orbiter stepper motor screws.  I replaced these screws with slightly longer 20mm screws, and added nylon stand-offs (see the photos).  I had to screw two standoffs together to make the 30mm distance.  The 'pillar' that the umbilical mounts to is deliberately offset to allow the pigtail to curve a bit for some strain relief.  At least that was the idea.

    Alternate mount for 4028 fan, including protective inlet grille.

        This is necessary to provide clearance for the NiteHawk 36 mount wires.
        On my machine, it cleared the rear Z leadscrew without modification, but this may
        depend on how you've adjusted your Y endstop.

        There's also a Zip-tie mount on one side, which I used to secure the Beacon wires.

    Modified "Top Endstop" piece to accomodate a bare endstop switch.

        I went this route because I already had a bag of these switches.  If you're going to make custom-length wires anyway, I think these are just as easy.

    Minimalist grille for front fan.

        I re-used this from some other project.  It's not in the Onshape document.

Released under CC 4.0 share-alike license.
    https://creativecommons.org/licenses/by-nc-sa/4.0/

My thanks to all Ratrig and Eva contributors!

-Matt Keveney
keveney.com
