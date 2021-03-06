# Human-Acitivity-Recognition

Requirements
------------
1. MATLAB R2013a  
2. WEKA 3.7

Usage 
-----

####Installation

1. Download zip 
2. Unzip 
3. Open recognizer.m in MATLAB 

####MATLAB command line
```matlab
recognizer <weka_path> <video_name>;
```
####Example
```matlab
recognizer 'C:\Program Files\Weka-3-7\weka.jar' video.avi;
```

Output
------
###Original video frame
[![frame.png](https://s3.postimg.org/5a8votdrn/frame.png)](https://postimg.org/image/84c129fxr/)

###Human Segmented image
[![mask.png](https://s4.postimg.org/90btq8j71/mask.png)](https://postimg.org/image/nwacxtull/)

###Recognized Activity
[![box.png](https://s4.postimg.org/nukgkv8v1/box.png)](https://postimg.org/image/w02ij0x3t/)

Reference Paper
---------------
N.Ikizler and P.Duygulu. Human Action Recognition Using Distribution of Oriented Rectangular Patches.  
*In: Springer Human Motion 2007, LNCS 4814, pp. 271–284*,2007. 

License
-------
[![License](https://s3.postimg.org/5h9joly3n/license.png)](https://postimg.org/image/g43cu168v/)
