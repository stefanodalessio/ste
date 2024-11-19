
## Install and run with Processing on mac

 >[!info] this works for both kinect 1414 and kinect ONE
 > use processing 3 if possible
 

- Download [openkinect library](https://github.com/shiffman/OpenKinect-for-Processing/releases/download/1.0/openkinect_processing.zip)
- place in /Documents/Processing/libraries
- go to /Documents/Processing/libraries/openkinect_processing/library/v1/mac
- right click and open: libfreenect.dylib (nothing visible happens and it's ok)
- right click and open: libusb-1.0.0.dylib (nothing visible happens and it's ok)
- run your processing sketch (remember that processing files always needs to be located in /Documents/Processing/ preferably in a personal folder)

#### processing 4

If you can't run processing 3 keep in mind that libfreenect is not arm compatible, so to run it on processing 4 you need to get processing 4 intel version, run it in rosetta and do this:
https://discourse.processing.org/t/processing-4-openkinect/32781/9

