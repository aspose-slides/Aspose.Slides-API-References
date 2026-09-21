---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chart/get_image/
weight: 40
---
## get_image(self) {#}
Shape thumbnail을 반환합니다.
            ShapeThumbnailBounds.Shape 형태의 모양 썸네일 경계 유형이 기본적으로 사용됩니다.

### Returns

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Shape thumbnail을 반환합니다.

### Returns

Shape thumbnail 또는 ShapeThumbnailBounds.Appearance이 사용되고 모양에 표시 요소가 없을 경우 None을 반환합니다.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds) | Shape thumbnail 경계 유형입니다. |
| scale_x | **float** | X 스케일 |
| scale_y | **float** | Y 스케일 |

### 참조
* 클래스 [`Chart`](/slides/python-net/ko/aspose.slides.charts/chart)
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 열거형 [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)