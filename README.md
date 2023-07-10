# OAI Segmentation Annotations
This is the segmentation annotations for the "CAS-Net: Cross-view Aligned Segmentation by Graph Representation of Knees" paper. 

## 2D Segmentation 
The segmentation files can be found in the "data" folder and include sagittal, coronal, and axial views. 
And the data index, OAI uid, and sequence name are listed in the "data_index_2d.csv" file.

## 3D Segmentation
The 3D segmentation is required from Ambellan et al., which can be accessed from [OAI-ZIB](https://pubdata.zib.de/). 
We really appreciate their excellent work. 
The data information for 3D segmentation is similar to the 2D data and can be found in the "data_index_3d.csv" file.

## Misaligned Cases
We find that some of the subjects have knee motion during the knee MRI scanning process, resulting in image misalignment between different view/sequences. 
It reduces the cross-view segmentation performance of our method. 
These cases are listed in the "misaligned_cases.csv" file.

## Cite
If you use the 2D multi-view segmentation annotations in a scientific publication, we would appreciate citations to the following paper:

```
@article{zhuang2023cas,
    title={CAS-Net: Cross-view Aligned Segmentation by Graph Representation of Knees},
    author={Zixu Zhuang and Xin Wang and Sheng Wang and Zhenrong Shen and Xiangyu Zhao and Mengjun Liu and Zhong Xue and Dinggang Shen and Lichi Zhang and Qian Wang},
    booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
    year={2023},
    organization={Springer}
}
```