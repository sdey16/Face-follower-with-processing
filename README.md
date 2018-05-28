# Face follower with Processing 3 and Arduino



<h3>Note: This code is valid only for Processing 3 with the opencv_processing and video library.</h3>

<h2>Steps to use this code:</h2>
<ol>
  <li>First install libraries opencv_processing and video from <a href="https://drive.google.com/file/d/1SW2uwrFtu9Nq_sAf91RnD2FM77b6wm5l/view?usp=sharing">here</a></li>
  <li>Copy these files to documents/Processing/libraries</li>
      <li>Download the Arduino code from <a href="http://sfecdn.s3.amazonaws.com/downloads/tutorials/PanTiltFaceDetection/SerialServoControl.zip">here</a> and upload it to the Arduino.</li>
  <li>Run the Processing 3 sketch given in this respository</li>
          </ol>
<h2>Troubleshooting:</h2>
Problems can arise due to the following reason:
<ol>
  <li><strong>Port selected may be wrong:</strong> A list of ports are displayed at the compilation output screen. By default the first port is selected. However, if your Arduino is present on a different port, replace [0] in 'port = new Serial(this, Serial.list()[0], 57600);' with the position of the port number of Arduino. For example: If in the list of ports your port is on third position, replace [0] with [2].</li>
  <li><strong>Camera could not be initialized:</strong> This may occur due to lack of permissions. To solve this, re-run the code. Network permissions would be required. Provide them.</li>
  </ol>
  
  
  <h2>In case of any problem, feel free to contact the author.</h2>
