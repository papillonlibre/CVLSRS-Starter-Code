Testing IP addresses. Note that these changes subject to whether the Pi is in or out of the robot
and also based on which WiFi you are connected to.

IP: 192.168.0.178
IP: 192.168.0.102
IP: 192.168.0.160


For future reference, this was run on the Tufts Robotics WiFi (TP_Link_Tufts-Robotics) using
the appropriate IP addresses. The robomodules were each run on an instance of PowerShell. The 
command to transfer the code from the local PC to the Pi itself was:

scp -r &lt;FOLDER TO BE DOWNLOADED TO TARGET&gt;pi@&lt;IP ADDRESS&gt;:

The command to run each of the modules (note: classes that are not modules such as camera_reader.py
did not need to be run in this way) was of the form:


python3 &lt;fileName&gt;
