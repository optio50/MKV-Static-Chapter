![ScreenShot](https://raw.githubusercontent.com/optio50/MKV-Static-Chapter/main/ScreenShot.png?raw=true|alt=octocat)

# MKV-Static-Chapter
Add fixed chapter lengths to MKV files.   
Can do batch or single files.   

Passing just a directory will process all mkv's in that directory at a single depth.

Batch   

```Static-Chap -s 7 "/media/optio/Videos"```

Single   

```Static-Chap -s 7 "/media/optio/Videos/Bones - S12E10 - The Radioactive Panthers in the Party.mkv"```   
   
   Option "-s" is the requested chapter length in Min.   
   Default is 5 Min without option "-s"   
      
   Processing is extreamly fast.   
   Files are NOT re-encoded.   
   Mkvpropedit & ffprobe are required.   
