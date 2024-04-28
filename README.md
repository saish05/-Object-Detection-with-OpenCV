# Object Detection using YOLO with OpenCV

This project utilizes the YOLO (You Only Look Once) object detection algorithm implemented in OpenCV to detect objects in images. YOLO is a state-of-the-art, real-time object detection system that can detect multiple objects in an image with high accuracy and efficiency.

## Usage

### Prerequisites
- Python 
- OpenCV
- Numpy

### Running the Script
1. Clone the repository or download the script (`object_detection_yolo.py`) to your local machine.
2. Open a terminal or command prompt and navigate to the directory containing the script.
3. Run the script using the following command:
   ```
   python object_detection_yolo.py -i <path_to_input_image> -c <path_to_config_file> -w <path_to_weights_file> -cl <path_to_classes_file>
   ```
   Replace `<path_to_input_image>`, `<path_to_config_file>`, `<path_to_weights_file>`, and `<path_to_classes_file>` with the respective paths to your input image, YOLO config file, YOLO pre-trained weights file, and class names file.

### Output
The script will display the input image with bounding boxes drawn around detected objects. Press any key to close the image window. Additionally, the script will save the annotated image as `object-detection.jpg` in the same directory.

## Files

- `object_detection_yolo.py`: Python script for object detection using YOLO with OpenCV.
- `README.md`: Documentation file providing instructions and information about the project.
- `object-detection.jpg`: Annotated image with bounding boxes drawn around detected objects (output of the script).

## References
- [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/)
- [OpenCV Documentation](https://opencv.org/)
