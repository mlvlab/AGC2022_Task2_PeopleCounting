# AGC2022 Task2 PeopleCounting
original cloned repository: https://github.com/mikel-brostrom/Yolov7_StrongSORT_OSNet

## Video Data & Pretrained Params
https://drive.google.com/drive/folders/1CfVMSrl-t0t2sMdNLMnU23oKJSOd1dQS?usp=sharing

## Video Inference Command

Task2 @ "src/"
```shell
python task2_vision.py
--config_strongsort task2_vision/strong_sort/configs/strong_sort.yaml \
--strong_sort_weights task2_vision/weights/osnet_x0_25_msmt17.pt \
--yolo_weights task2_vision/weights/task2_final.pt \
```

