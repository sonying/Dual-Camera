# Dual-Camera
Encoding video of both front and back side cameras in one video file using MediaCodec.
This apps purpose is to reduce the workload of video decoding on the processor. The idea of doing this came out from the records of the CCTV cameras on a truck. Since there are many cameras on a truck for security, analyzing this records simultaneously requires a powerful processor or before analyzing, all this records need to be merged into one file with some software.<p> With this project we show that with using efficient merging technique during the recoding on Android platform there no need to use another software for merging the records after the recording session finished. <p>The two streams from front and back cameras on an android phone has been merged successfully and at the analying process instead of decoding two video files only one video file can be decoded. Currently the resolution is at the 640 * 480 value for each stream (which makes the resolution of the resulted video 640 * 960) with 30fps frame rate for the merged video. Tested frame rate for 1280 * 720 resolution value is 18fps. 
<p>You can download a sample of the mp4 file created using this app from this <a href="https://gaziedutr-my.sharepoint.com/personal/ahmet_bekir_urun_gazi_edu_tr/_layouts/15/guestaccess.aspx?docid=1f1ec9afec61f4b8fbbb2b1ecc926a559&authkey=AdPAgAZbH7RGYitHLpkiBS4">link</a>.

## Currently supported boards 
* RK3399  
NanoPC T4  
NanoPC M4  
NanoPC NEO4  
Som-RK3399  

Tested on Android8.1
