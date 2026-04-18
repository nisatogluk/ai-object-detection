
# Model Card: Industrial Object Detector

## Model Details
- **Architecture:** YOLOv8m
- **Task:** Object Detection
- **Input Size:** 640x640

## Training Data
- **Source:** Roboflow Dataset

### Augmentations
- Outputs per training example: 3
- Flip: Horizontal
- Rotation: Between -15° and +15°
- Brightness: Between -15% and +15%
- Exposure: Between -10% and +10%

## Performance
- **mAP50:** 0.9395
- **mAP50-95:** 0.8613
- **Precision:** 0.8252
- **Recall:** 0.8462

## Limitations
- Works best in indoor lighting
- May struggle with extreme occlusions
- May struggle with very worn plastic packaging
