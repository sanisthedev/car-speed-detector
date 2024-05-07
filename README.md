<H1 align="center">
YOLOv8 Object Detection with DeepSORT Tracking(ID + Trails) </H1>

- Install the dependecies
```
pip install -e '.[dev]'

```

- Command Line.
```
cd ultralytics/yolo/v8/detect
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```