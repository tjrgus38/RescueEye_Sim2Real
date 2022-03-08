# RescueEye_Sim2Real

## 조난자 데이터셋을 YOLOv5를 이용하여 학습하고, Objects detection과 데이터 증강을 통해 모델 성능 개선.
- 효과적인 Data Augmentation 찾기
- Detection에 실패한 이미지에 대해 CAM 분석을 통해 설명 가능한 AI


> SARD 약 4.5GB
> - 이미지 크기 : 1920*1080
> - 레이블 : 사람(Person)


> PABLO 합성 데이터 약 45GB
> - 이미지 크기 : 3840*2160
> - 레이블 : Person, Pad, Pablo Mark


![모델1](https://user-images.githubusercontent.com/90364187/157182090-f380aad5-8e2f-4e15-940e-852efdd8e1ce.png)
- 진행 중인 프로세스


![사진](https://user-images.githubusercontent.com/90364187/157182227-956c7276-8d88-49bd-9657-f8e0a21de3c1.png)
- SARD 예시 이미지


![17](https://user-images.githubusercontent.com/90364187/157182315-b2bf7133-1df9-4ad9-91e3-5b9335c47e0a.png)
- 17번 heatmap


![20](https://user-images.githubusercontent.com/90364187/157182357-87371f93-d7f6-487a-84fd-22020ac95a31.png)
- 20번 heatmap

![23](https://user-images.githubusercontent.com/90364187/157182387-59f2615e-47f9-4d19-8d3a-c915cb25eca8.png)
- 23번 heatmap

**히트맵을 보고 난뒤 중간발표 이후에는 YOLOv5의 구조를 바꾸거나 Augmentation 중 Copy paste를 적용해볼 예정.**


![YOLO 구조](https://user-images.githubusercontent.com/90364187/157182733-cd84fbff-ed2b-4d3d-bc64-d57acdf8a0fd.png)
- YOLO의 구조에서 17번 20번 23번이 가장 중요

![프로세스](https://user-images.githubusercontent.com/90364187/157182891-d836b8eb-b983-41aa-a38b-6721f4dead58.png)

- 최종적으로 진행된  프로세스
