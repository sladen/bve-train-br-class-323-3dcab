=====================================
Class 323 25kV AC EMU - Unrefurbished 
     3D Cab Update for openBVE

         railsimroutes.net
       trainsimcentral.co.uk
=====================================

Introduction
------------

This new 3D cab is a pre-release preview, and comes complete with working gauges, as well as an animated traction/brake controller, reverser, AWS reset button, and horn lever, along with working TPWS indicators, AWS sunflower, DRA, and other indicators as well. Cab lighting is also included, along with semi-functional headlights (but not in the daytime headlight configuration).

Together with openBVE v1.2’s new Interior (Look Ahead) camera view accessible by pressing F1 until the new view mode is selected, the Mouse Grab option enabled by clicking the Right Mouse Button within openBVE’s 3D view, as well as the driver’s body/head motion simulation model, you’ll now be able to enjoy a much more realistic and immersive driving experience.

Thanks goes to Steve Green for his advice on making the cab layout more accurate in this initial release, and to both Steve and Steve Thomas for the original 2D panel and photos, on which some of the textures used in this add-on are based.

Notes
-----

Please note that this 3D cab isn’t finished yet, and various details are missing. Major issues in this initial release:

    * Wiper animation is inadequate, and wiper control knob isn’t implemented yet
    * Raindrop effects aren't implemented yet
    * Headlight effects may need some work
    * No details added to the rear of the cab behind the driver; ceiling details are likely inaccurate
    * The seats are comprised of only temporary meshes

More updates will follow later.

Also, this 3D cab can have BVE4 style timetable textures displayed on a dedicated mesh within the cab, when used with openBVE 1.2.7.0 or greater. However, this feature is disabled by default, so the timetable texture is shown as a part of openBVE's in-game UI instead. If you want to experiment with this feature, please uncomment the following lines near the top of the panel.animated file:

;[Object]
;States = 3d_cab\timetable.csv
;textureoverride = timetable

Usage
-----

This add-on has been released into the public domain. However, if this isn't legally possible, then no conditions, restrictions or requirements are placed upon the use, modification or redistribution of this add-on. I would be grateful for acknowledgement, but this isn't required.

==============
Anthony Bowden
July, 2010