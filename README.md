# pi-ffcam
Trivial app to preview the RPi camera output on the RPi3 and RPi4

Streams 640x480 video from /dev/video0 using h264, then decodes it again using a software codec and displays in an SDL window.

Intended just for use as a quick test that things are working - you wouldn't do it this way in a production setting ^-^
