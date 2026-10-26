---
title: get_image method
second_title: Aspose.Slides Python용 .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
도형 썸네일을 반환합니다.
            ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 기본적으로 사용됩니다.

### 반환

도형 썸네일.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
도형 썸네일을 반환합니다.

### 반환

Shape thumbnail 또는 ShapeThumbnailBounds.Appearance이 사용되고 도형에 표시 요소가 없을 경우 None을 반환합니다.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds) | 도형 썸네일 경계 유형. |
| scale_x | **float** | X 배율 |
| scale_y | **float** | Y 배율 |



### 참조
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 클래스 [`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe)
* 열거형 [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)