---
title: get_image method
second_title: Python용 Aspose.Slides (.NET API 레퍼런스)
description: 
type: docs
url: /ko/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
형태 썸네일을 반환합니다.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type이 기본값으로 사용됩니다.

### 반환

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
형태 썸네일을 반환합니다.

### 반환

Shape thumbnail 또는 ShapeThumbnailBounds.Appearance이 사용되고 shape에 보이는 요소가 없을 경우 None을 반환합니다.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X 스케일 |
| scale_y | **float** | Y 스케일 |

### 참고
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 열거형 [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds)
* 클래스 [`VideoFrame`](/slides/python-net/ko/aspose.slides/videoframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)