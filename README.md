# SMFDNet Demo Dataset

This repository provides a demo version of the self-built desktop test-tube object detection dataset used in the SMFDNet study.

The demo dataset contains representative images and YOLO-format annotations for four target categories:

1. Tube Cap
2. Reference Marker
3. Centrifuge Marker
4. Mini-Centrifuge Marker

The complete raw dataset contains continuous acquisition sequences, equipment operating states, and process records related to experimental procedure details. Therefore, the full raw dataset is not publicly released at this stage. This demo version is provided for academic reference and non-commercial research use, and is intended to illustrate the annotation format, target categories, and typical laboratory scenarios used in this study.

## Dataset Structure

images/train  
images/val  
images/test  
labels/train  
labels/val  
labels/test  

## Annotation Format

Annotations are provided in YOLO format:

class_id x_center y_center width height

All coordinates are normalized by the image width and height.

## Categories

| ID | Category |
|---|---|
| 0 | Tube Cap |
| 1 | Reference Marker |
| 2 | Centrifuge Marker |
| 3 | Mini-Centrifuge Marker |

## License

This demo dataset is released for academic research and non-commercial use only under the CC BY-NC 4.0 license.