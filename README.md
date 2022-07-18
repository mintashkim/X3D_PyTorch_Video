# pytorchvideo_x3d

pytorchvideo 라이브러리를 활용하여 i3d, x3d 등의 3d convolution based feature를 추출하는 코드

## 진행사항
- i3d, x3d 모델을 불러와 Classification layer를 제거해 Feature를 추출할 수 있도록 변경
- TenCrop 적용
- batch inference 가능하도록 코드 작성
- 짧은 영상에서 400 kinetics를 추출하고, 빈도수를 쌓아 시각화하는 코드 작성

## TODO
- 