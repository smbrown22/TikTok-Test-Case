# TikTok-Test-Case

<h2>Positive Tests</h2>

<h4>TC_Positive_Route_1</h4>
User Successfully uploads Video 

User is logged in 
Tap 'Upload', select myVideo.avi 
Size of myVideo.avi is 250 MB. 
Video length is 4 minutes, 6 seconds. 
Aspect Ratio is 9:16, Resolution is 720 x 1280. 
No caption. 

Expected: Video uploads successfully. High priority. 

<h4>TC_Positive_Route_2</h4> 
User Successfully uploads Video

User is logged in 
Tap 'Upload', select thoughts.mp4 
Size of thoughts.mp4 is 96 MB. 
Video length is 1 minute, 12 seconds. 
Aspect Ratio is 9:16, Resolution is 720 x 1280. 
Caption is 2000 characters.

Expected: Video uploads successfully. High priority. 

<h2>Negative Tests</h2> 

<h4>TC_Negative_Route_1</h4>
User is not able to upload Video

User is logged in 
Tap 'Upload', select landscape.mp3
Size of landscape.mp3 is 100 MB. 
Length is 40 seconds. 
No aspect ratio, no resolution. 

Expected: Unable to upload, file is in the incorrect format. High priority. 

<h4>TC_Negative_Route_2</h4> 

User is logged in 
Tap 'Upload', select %myFootage.mp4 
Size of %myFootage.mp4 is 232 MB. 
Length is 8 minutes, 7 seconds. 
Aspect Ratio is 9:16, Resolution is 720 x 1280.  

Expected: Unable to upload, file has a special character in the name. High priority. 

<h2>Boundary Tests</h2>

<h4>TC_Boundary_Route_1</h4>
User is not able to upload Video

User is logged in 
Tap 'Upload', select helloWorld.mp4 
Size of landscape.mp3 is 258 MB. 
Length is 601 seconds. 
Aspect Ratio is 9:16, Resolution is 720 x 1280.

Expected: Unable to upload, video is too long. Medium Priority 

<h4>TC_Boundary_Route_2</h4> 

User is logged in 
Tap 'Upload', select byeWorld.mp4 
Size of byeWorld.mp4 is 30 MB. 
Length is 3 seconds. 
Aspect Ratio is 9:16, Resolution is 720 x 1280.  

Expected: Unable to upload, file has a special character in the name. High priority 

<h2>Black Box Tests</h2> 

<h4>TC_BlackBox_Route_1</h4>
User is not able to upload Video

User is logged in 
Tap 'Upload', select helloWorld.mp4 
Size of helloWorld.mp4 is 258 MB. 
Length is 500 seconds. 
Aspect Ratio is 9:16, Resolution is 720 x 1280.

Expected: Fine to upload.  

<h4>TC_BlackBox_Route_2</h4> 

User is logged in 
Tap 'Upload', select *bloopBleep.mp4 
Size of *bloopBleep.mp4 is 56 MB. 
Length is 30 seconds. 
Aspect Ratio is 9:16, Resolution is 720 x 1280.  

Expected: Unable to upload, file has a special character in the name. 

<h2>Edge Cases Tests</h2> 

<h4>TC_Edge_Route_1</h4>
User is not able to upload Video

User is logged in 
Tap 'Upload', select bloop.mp4 
Size of bloop.mp4 is 258 MB. 
Length is 601 seconds. 
Aspect Ratio is 9:16, Resolution is 720 x 1280.

Expected: Unable to upload, video is too long. 

<h4>TC_Edge_Route_2</h4> 

User is logged in 
Tap 'Upload', select bleep.mp4 
Size of bleep.mp4 is 30 MB. 
Length is 15 seconds. 
Aspect Ratio is 9:16, Resolution is 720 x 1280.
File has been corrupted. 

Expected: Unable to upload, file has been corrupted. High priority. 
