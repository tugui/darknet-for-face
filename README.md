# darknet-for-face
### Convert Command
```
./darknet partial cfg/yolov3-tiny.cfg yolov3-tiny.weights yolov3-tiny.conv.15 15
```
### Train Command
```
./darknet detector train ./cfg/voc-face.data ./cfg/yolov3-tiny-face.cfg ./yolov3-tiny.conv.15
```
### Test Command
```
./darknet detector test ./cfg/voc-face.data ./cfg/yolov3-tiny-face.cfg backup/yolov3-tiny-face_final.weights /path/to/image
```
