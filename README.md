# Building a custom object detector using YOLO

In this repository, I put the code and the dataset of my rubik's cube to building a custom object detector to detect rubik's cube using the tiny YOLO v2.
	
  In the next table, I briefly described the contents of this repository.

  <table class="table table-bordered table-striped" style="margin: 0 auto !important;float: none !important;width: auto;"> <thead> 									
	<tr> <td>Name</td> <td>Its Function</td> </tr> </thead>
	 <tbody> 
     	 <tr> <td>Dataset</td> <td>Folder contains the images and annotation files.</td> </tr> 
          	 <tr> <td>model.data</td> <td>Pre-trained model to detect rubik's cube.</td> </tr> 
	 <tr> <td>YoloTrainer.java</td> <td>Training Yolo with our custom dataset.</td> </tr> 
	<tr> <td>RubixDetector.java</td> <td>Real-time rubik's cube detector, it reads a stream of frames from the webcam the then detects the rubik's cube in each one.</td> </tr> 
	<tr> <td>YoloModel.java</td> <td>Loading the trained model by the class YoloTrainer and make the detection given an image.</td> </tr> 
	<tr> <td>NonMaxSuppression.java</td> <td>Implementation of the non-maximum suppression algorithm to cope the problem of detecting the same object multiple times by the yolo algorithm.</td> </tr> 
	 </tbody></table>
   <br><br>
   
   
   
   
**For more info**

Comming Sooooon

