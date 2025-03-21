# YOLOtrash
We created the YOLOtrash for the purpose of robot trash pickup.

The data format is YOLO.
Conversion to other data formats (COCO, PascalVOC, etc.)
Please refer to the following github for conversion to other data formats (COCO, PascalVOC, etc.).
* https://github.com/ssaru/convert2Yolo.git
* https://github.com/JPM-Tech/Object-Detection/blob/main/Scripts/converters/convert-yolo-to-xml.py

Or, please refer to the program in /data when you unzip the zip file.
Please use it if you like.

# Dataset
This repository contains the dataset that we collected. The dataset spans four classes: can, bottle, cardboard, and cigarette. Currently, the dataset consists of 8412 images:

train number of imgaes:6731 background:49
* Can 2721
* Bottle 2582
* Cardboard 1643
* Cigarette 3638

valid number of imgaes:1681 background:12
* Can 287
* Bottle 941
* Cardboard 179
* Cigarette 545

 **If you are using the dataset, please download the dataset from  [here](https://drive.google.com/file/d/1m51Q_9ZUHXdKcNk_B0Ud26dvTxc-XLHM/view?usp=sharing).**

# Ref
We are publishing our own model trained with this YOLOtrash. If you use it, please cite the following paper.

```
@article{Ryotaro Harada2023,
  title={Trash Detection Algorithm Suitable for Mobile Robots Using Improved YOLO},
  author={Ryotaro Harada and Tadahiro Oyama and Kenji Fujimoto and Toshihiko Shimizu and Masayoshi Ozawa and Julien Samuel Amar and Masahiko Sakai},
  journal={Journal of Advanced Computational Intelligence and Intelligent Informatics},
  volume={27},
  number={4},
  pages={622-631},
  year={2023},
  doi={10.20965/jaciii.2023.p0622}
}
```

