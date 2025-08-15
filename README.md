# Detecting-and-Tracking-people-in-a-video-clip
A basic Deep Learning project, using YOLO v11 for detection and Deep Sort for tracking detected persons. Also fine tuning is done to YOLO v11 model for better Person Detection.

# Steps to run the code
1) First install python and Git in your laptop.
2) Download/clone this repository on your laptop.
3) Navigate to the repository downloaded.
4) Now  run the ipynb file deploy_final.ipynb.
5) Make shore that deploy_final.ipynb and data folder are in the same folder on your laptop.
6) On running the file if you get the error for any modules not installed download them,this might be the only error you might get.
7) If the file deploy_final.ipynb ran succesfully in the output of the last cell of the ipynb file you will get a link.
8) Please open the link and upload the video.
9) You will always be able to download the output and view it.

#  Hyperparameters
### tracker=DeepSort(max_age=30,n_init=10,nn_budget=200,nms_max_overlap=0.3,max_iou_distance=0.6,max_cosine_distance=0.3,embedder='torchreid',embedder_model_name='osnet_x1_0')

This is the part of the code that contains the hyperparameters and the default hyperparameters are clearly mentioned in the code.You can read about the hyperparameters from the report and change them accordingly.
