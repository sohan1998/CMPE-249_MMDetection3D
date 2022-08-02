# 3D OBJECT DETECTION Homework Assignment 

## INTRODUCTION:
<b> Name: Sohan Shirodkar <br> Course: CMPE-249 </b> <br>

## SETUP:
[Link used for reference](https://mmdetection3d.readthedocs.io/en/latest/index.html) <br>
[Link used for HPC setup](http://coe-hpc-web.sjsu.edu/) <br>

### EVALUATION:
> Calculate overlap between two set of bboxes. If 'is_aligned' is 'False',  calculate the ious between each bbox of bboxes1 and bboxes2.

<b> Command: </b>
> bash tools/dist_test.sh configs/pointpillars/hv_pointpillars_secfpn_6x8_160e_kitti-3d-3class.py work_dirs/hv_pointpillars_secfpn_6x8_160e_kitti-3d-3class/latest.pth 1 --eval bbox

## REPORT:
[CMPE249_HW_3D_Object_Detection.pdf](https://github.com/sohan1998/CMPE-249_MMDetection3D/files/9238141/CMPE249_HW_3D_Object_Detection.pdf)
