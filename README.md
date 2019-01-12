# All the components needed to compile poppler on Ubuntu 18.x
## Includes
* fontconfig-2.12.6
* libjpeg-turbo-1.5.3
* freetype-2.9
* poppler-data-0.4.9
* poppler-0.72.0

## Getting it to compile
```
 on ubuntu unzip the tar file
 cd to each of the folder and follow the instruction given in the
 INSTALL file. 
 Typical steps are 
 ./configure
 make
 sudo make install
```
 compile poppler-0.72.x as a last step so that it can find all the 
 dependent libraries.



