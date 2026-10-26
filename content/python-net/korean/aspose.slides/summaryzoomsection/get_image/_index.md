---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/summaryzoomsection/get_image/
weight: 30
---
## get_image(self) {#}
형상 썸네일을 반환합니다.
            기본값으로 ShapeThumbnailBounds.Shape 형상 썸네일 경계 유형이 사용됩니다.

### 반환

형상 썸네일.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
형상 썸네일을 반환합니다.

### 반환

ShapeThumbnailBounds.Appearance가 사용되고 형상에 보이는 요소가 없을 경우 None을 반환합니다.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds) | 형상 썸네일 경계 유형. |
| scale_x | **float** | X 축 스케일 |
| scale_y | **float** | Y 축 스케일 |



### 참고
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 열거형 [`ShapeThumbnailBounds`](/slides/python-net/ko/aspose.slides/shapethumbnailbounds)
* 클래스 [`SummaryZoomSection`](/slides/python-net/ko/aspose.slides/summaryzoomsection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)