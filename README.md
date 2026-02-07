A Diffusion Model-Based Landslide Detection Method for Optical Remote Sensing Images

IEEE Geoscience and Remote Sensing Letters

Authors: Liangxun Zhang , Jianjian Gao, Yuanchao Su, Xu Sun, Mengying Jiang, Jiaxin Cheng, and Ronghua Liu

Code for the paper: A Diffusion Model-Based Landslide Detection Method for Optical Remote Sensing Images

The codebases are built on top of [Detectron2](https://github.com/facebookresearch/detectron2), [DiffusionDet](https://github.com/ShoufaChen/DiffusionDet)

## Requirements
- Python ≥ 3.6
- PyTorch ≥ 1.9.0 and [torchvision](https://github.com/pytorch/vision/) that matches the PyTorch installation.
  You can install them together at [pytorch.org](https://pytorch.org) to make sure of this
- OpenCV is optional and needed by demo and visualization
-  Install Detectron2 (https://github.com/facebookresearch/detectron2)


## How to run our code

- Parameters: All the parameters that need fine-tuning can be found in `config.py` and `diffdet.voc.res50.yaml`.``

- Train: Train the model by `train_net.py`

- Visualize: Run `demp.py` to obtain the detection visualization results


### Contact
If you happen to encounter any bugs while using this code, please do not hesitate to contact us.

Liangxun Zhang (zlx13317969097@163.com).
Yuanchao Su (suych@um.edu.mo / suych3@xust.edu.cn)
