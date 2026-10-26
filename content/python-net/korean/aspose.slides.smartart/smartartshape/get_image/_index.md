---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
형태 썸네일을 반환합니다.
            ShapeThumbnailBounds.Shape shape thumbnail bounds 유형이 기본값으로 사용됩니다.

### 반환값

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Shape thumbnail을 반환합니다.

### 반환값

Shape thumbnail 또는 ShapeThumbnailBounds.Appearance이 사용되고 형태에 보이는 요소가 없을 경우 None을 반환합니다.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds 유형. |
| scale_x | **float** | X 스케일 |
| scale_y | **float** | Y 스케일 |

### 참고
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 열거형 [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds)
* 클래스 [`SmartArtShape`](/slides/python-net/ko/aspose.slides.smartart/smartartshape)
* 모듈 [`aspose.slides.smartart`](/slides/python-net/ko/aspose.slides.smartart)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)