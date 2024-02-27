# RCooper: A Real-world Large-scale Dataset for Roadside Cooperative Perception
<!-- [![website](https://img.shields.io/badge/Website-Explore%20Now-blueviolet?style=flat&logo=google-chrome)](https://research.seas.ucla.edu/mobility-lab/v2v4real/)
[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2303.07601.pdf)
[![supplement](https://img.shields.io/badge/Supplementary-Material-red)](https://arxiv.org/pdf/2303.07601.pdf)
[![video](https://img.shields.io/badge/Video-Presentation-F9D371)]() -->


This is the official implementation of CVPR2024 paper. "RCooper: A Real-world Large-scale Dataset for Roadside Cooperative Perception".
[Ruiyang Hao](https://ry-hao.top/),  [Siqi Fan](https://leofansq.github.io/), [Yingru Dai](https://dblp.org/pid/350/9258.html), [Zhenlin Zhang](https://www.linkedin.com/in/zhenlinzhangtim/), [Chenxi Li](),  [Yuntian Wang](), [Haibao Yu](https://scholar.google.com/citations?user=JW4F5HoAAAAJ), [Wenxian Yang](https://scholar.google.com/citations?user=Kiz73xwAAAAJ), [Jirui Yuan](https://air.tsinghua.edu.cn/en/info/1012/1219.htm), [Zaiqing Nie](https://air.tsinghua.edu.cn/en/info/1046/1192.htm)

<p style="text-align:center">
<img src="assets/demo/dataset_demo1.gif" width="400" alt="" class="img-responsive">
<img src="assets/demo/dataset_demo2.gif" width="400" alt="" class="img-responsive"></br>
<img src="assets/demo/dataset_demo3.gif" width="400" alt="" class="img-responsive">
<img src="assets/demo/dataset_demo4.gif" width="400" alt="" class="img-responsive">
</p>

## Overview
- [Data Download](#data-download)
- [Benchmark](#benchmark)
- [Citation](#citation)
- [Acknowledgment](#known-issues)

## Data Download
Please check the bottom of this page [website](https://www.t3caic.com/qingzhen/) to download the data.

<!-- After downloading the data, please put the data in the following structure: -->
<!-- ```shell
├── v2v4real
│   ├── train
|      |── testoutput_CAV_data_2022-03-15-09-54-40_1
│   ├── validate
│   ├── test
``` -->

<!-- 
## Devkit setup
To be supplemented.
 -->

<!-- 
## Quick Start
To be supplemented. -->

## Benchmark
### Results of Cooperative 3D object detection for corridor scenes
To be updated.
<!-- | Method       | AP@0.3 | AP@0.5 | AP@0.7 | Download Link|
|--------------|----------------|----------------|--------------|--------------|
| No Fusion    | 58.1 | 44.1 | 23.8          |    [url]()   |
| Late Fusion  | **65.1** | **47.6** | 24.4         |      [url]()     |
| Early Fusion | 50.0 | 33.9 | 18.3       |       [url]()     |
| [Attentive Fusion](https://arxiv.org/abs/2109.07644)     | 44.0 | 40.0 | 27.0     |  [url]() |
| [F-Cooper](https://arxiv.org/abs/1909.06459)             | 49.5 | 32.0 | 12.9     |  [url]() |
| [Where2Com](https://arxiv.org/abs/2209.12836)            | 50.0 | 42.0 | 30.0     |  [url]() |
| [CoBEVT](https://arxiv.org/abs/2207.02202)               | 53.1 | 45.3 | **33.0**  | [url]() | -->

### Results of Cooperative 3D object detection for intersection scenes
| Method       | AP@0.3 | AP@0.5 | AP@0.7 | Download Link|
|--------------|----------------|----------------|--------------|--------------|
| No Fusion    | 58.1 | 44.1 | 23.8          |    [url]()   |
| Late Fusion  | **65.1** | **47.6** | 24.4         |      [url]()     |
| Early Fusion | 50.0 | 33.9 | 18.3       |       [url]()     |
| [Attentive Fusion](https://arxiv.org/abs/2109.07644)     | 44.0 | 40.0 | 27.0     |  [url]() |
| [F-Cooper](https://arxiv.org/abs/1909.06459)             | 49.5 | 32.0 | 12.9     |  [url]() |
| [Where2Com](https://arxiv.org/abs/2209.12836)            | 50.0 | 42.0 | 30.0     |  [url]() |
| [CoBEVT](https://arxiv.org/abs/2207.02202)               | 53.1 | 45.3 | **33.0**  | [url]() |

### Results of Cooperative tracking for corridor scenes
To be updated.
<!-- | Method       | AMOTA(↑) | AMOTP(↑) | sAMOTA(↑) | MOTA(↑)  | MT(↑)    | ML(↓)    |
|--------------|----------|----------|-----------|----------|----------|----------|
| No Fusion    | 18.11    | 39.71    | 58.29     | 49.16    | 35.32    | 41.64    |
| Late Fusion  | **21.57**    | 43.40    | **63.02**     | **50.58**    | **42.75**    | **34.20**    |
| Early Fusion | 21.38    | **47.71**    | 62.93     | 50.15    | 36.80    | 42.75    |
| AttFuse      | 11.82    | 36.59    | 46.70     | 39.38    | 29.00    | 53.90    |
| F-Cooper     | -4.86    | 14.71    | 0.00      | -45.66   | 11.52    | 50.56    |
| Where2Com    | 14.19    | 38.47    | 51.30     | 42.24    | 29.00    | 45.72    |
| CoBEVT       | 14.81    | 38.78    | 49.45     | 44.63    | 33.83    | 35.69    | -->

### Results of Cooperative tracking for corridor scenes
| Method       | AMOTA(↑) | AMOTP(↑) | sAMOTA(↑) | MOTA(↑)  | MT(↑)    | ML(↓)    |
|--------------|----------|----------|-----------|----------|----------|----------|
| No Fusion    | 18.11    | 39.71    | 58.29     | 49.16    | 35.32    | 41.64    |
| Late Fusion  | **21.57**    | 43.40    | **63.02**     | **50.58**    | **42.75**    | **34.20**    |
| Early Fusion | 21.38    | **47.71**    | 62.93     | 50.15    | 36.80    | 42.75    |
| AttFuse      | 11.82    | 36.59    | 46.70     | 39.38    | 29.00    | 53.90    |
| F-Cooper     | -4.86    | 14.71    | 0.00      | -45.66   | 11.52    | 50.56    |
| Where2Com    | 14.19    | 38.47    | 51.30     | 42.24    | 29.00    | 45.72    |
| CoBEVT       | 14.81    | 38.78    | 49.45     | 44.63    | 33.83    | 35.69    |

## Citation
```shell
@inproceedings{hao2024rcooper,
  title={RCooper: A Real-world Large-scale Dataset for Roadside Cooperative Perception},
  author={Hao, Ruiyang and Fan, Siqi and Dai, Yingru and Zhang, Zhenlin and Li, Chenxi and Wang, Yuntian and Yu, Haibao and Yang, Wenxian and Jirui, Yuan and Nie, Zaiqing},
  booktitle={The IEEE/CVF Computer Vision and Pattern Recognition Conference (CVPR)},
  year={2024}
}
```

## Acknowledgment
- [V2V4Real](https://github.com/ucla-mobility/V2V4Real)
- [DAIR-V2X](https://github.com/AIR-THU/DAIR-V2X)
- [MMDetection3D](https://github.com/open-mmlab/mmdetection3d)
