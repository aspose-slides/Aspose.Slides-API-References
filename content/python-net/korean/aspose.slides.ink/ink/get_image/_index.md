---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
shape 썸네일을 반환합니다.
            기본적으로 ShapeThumbnailBounds.Shape shape thumbnail bounds 유형이 사용됩니다.

### 반환

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
shape 썸네일을 반환합니다.

### 반환

ShapeThumbnailBounds.Appearance가 사용되고 도형에 보이는 요소가 없는 경우 Shape thumbnail 또는 None을 반환합니다.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds 유형. |
| scale_x | **float** | X 스케일 |
| scale_y | **float** | Y 스케일 |

### 참조
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 클래스 [`Ink`](/slides/python-net/ko/aspose.slides.ink/ink)
* 열거형 [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds)
* 모듈 [`aspose.slides.ink`](/slides/python-net/ko/aspose.slides.ink)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)