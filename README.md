# Feature Space-Based Lightweight Anomaly Synthesis for Efficient Industrial Anomaly Detection
![img](https://img2023.cnblogs.com/blog/3211184/202501/3211184-20250113235941990-195365734.jpg)
```
@article{li2025toass,
  title={Feature Space-Based Lightweight Anomaly Synthesis for Efficient Industrial Anomaly Detection},
  author={Li, Shenbin and Jia Ruisheng},
  journal={The Visual Computer},
  year={2025}
}
```

## Introduction

------

This repo contains source code for **TOASS** implemented with pytorch.

TOASS is a lightweight self-supervised framework for industrial anomaly detection. It employs a Feature Fusion Adapter (FFA) to enhance feature representation and an Anomaly Detection Module (ADM) to synthesize anomalies, enabling efficient real-time performance without labeled data.

## Get Started

------

### Environment

Use the following commands:
```
pip install -r requirements.txt
```

### Data

Edit `run.sh` to edit dataset class and dataset path.

#### MvTecAD

Download the dataset from [here](https://www.mvtec.com/company/research/datasets/mvtec-ad/).

The dataset folders/files follow its original structure.

### Run

#### Demo train

Please specicy dataset path (line1) and log folder (line10) in `run.sh` before running.

`run.sh` gives the configuration to train models on MVTecAD dataset.

```
bash run.sh
```

## Acknowledgement

------

Thanks for great inspiration from [PatchCore](https://github.com/amazon-science/patchcore-inspection)

## License

------
All code within the repo is under [MIT license](https://mit-license.org/)



