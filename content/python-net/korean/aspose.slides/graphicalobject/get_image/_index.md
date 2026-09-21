---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
shape 썸네일을 반환합니다.
기본적으로 ShapeThumbnailBounds.Shape shape thumbnail bounds type이 사용됩니다.

### 반환값

Shape 썸네일.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
shape 썸네일을 반환합니다.

### 반환값

Shape thumbnail 또는 ShapeThumbnailBounds.Appearance이 사용되고 shape에 표시 요소가 없을 경우 None을 반환합니다.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds) | Shape 썸네일 경계 유형. |
| scale_x | **float** | X 스케일 |
| scale_y | **float** | Y 스케일 |

### 참조
* 클래스 [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject)
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 열거형 [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)