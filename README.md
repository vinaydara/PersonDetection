# PersonDetection
Person Detection using OpenVINO pre-trained models

Clone the project and run the python programe as below - 
python python person_detection_openvino.py --prototxt mobilenet-ssd.prototxt --model mobilenet-ssd.caffemodel

You can pass --confidence to let the model know the minimum probability to filter weak detections. 
Default is 0.9 which means the model will take action only if it detects an object with 90% or more probability.
