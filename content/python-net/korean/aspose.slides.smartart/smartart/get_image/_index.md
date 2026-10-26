---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
쉐이프 썸네일을 반환합니다.
            기본적으로 ShapeThumbnailBounds.Shape 쉐이프 썸네일 경계 유형이 사용됩니다.

### 반환값

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
쉐이프 썸네일을 반환합니다.

### 반환값

Shape thumbnail 또는 None을 반환합니다. ShapeThumbnailBounds.Appearance이 사용되고 쉐이프에 보이는 요소가 없을 경우.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds 유형. |
| scale_x | **float** | X 스케일 |
| scale_y | **float** | Y 스케일 |



### 또 보기
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 열거형 [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds)
* 클래스 [`SmartArt`](/slides/python-net/ko/aspose.slides.smartart/smartart)
* 모듈 [`aspose.slides.smartart`](/slides/python-net/ko/aspose.slides.smartart)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)