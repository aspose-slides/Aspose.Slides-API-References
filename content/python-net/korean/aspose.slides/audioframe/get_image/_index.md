---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
Returns shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### 반환값

Shape 썸네일.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returns shape thumbnail.

### 반환값

Shape thumbnail 또는 None, ShapeThumbnailBounds.Appearance이 사용되고 shape에 보이는 요소가 없는 경우.



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
* class [`AudioFrame`](/slides/python-net/ko/aspose.slides/audioframe)
* class [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)