/************************************************************************************************************
args
"frames 1 2 .." --- "frames 1 2 .. loop 3 4 .." --- "toggleWall"
*************************************************************************************************************/ 
    SpaceAnimagedGifs - A vanilla in-game script for playing animated gifs on LCDs 
     
    How to load an animated gif into the game. 
     
    1.  Go to http://spaceengineers.io/tools/storage-loader 
    2.  Drag your animated gif file into the gray box on that page. 
    3.  Depending on the size of the gif, it could take a little while to load. 
    4.  Copy each script under the file name on that page into the programming block in game and run the PB 
        once for each one.  (NOTE: Make sure you don't have a timer running the PB while your are doing this. 
        If the script runs more than once for any of the storage loader scripts, it won't work) 
    5.  Load this script into the PB and run it.
    6.  Wait.  After a little while (can take up to a few minutes depending on how big the gif is) the gif will 
        start playing. Some GIFs may not work.
         
    Note: Adjust the throttle below if you get complexity errors. 
    
    You can use programming block arguments to change which frame(s) are played.  Ex: "frames 1 3 5 7" will 
    play frames 1, 3, 5 and 7, then stop.  If you add loop into the list of frames, it will play each frame until the
    loop and then loop the remaining frames. Ex: "frames 1 2 3 4 5 loop 6 7 8 9 10"
        
    Fork on github: http://github.com/rockyjvec/SpaceAnimatedGifs 
*************************************************************************************************************/