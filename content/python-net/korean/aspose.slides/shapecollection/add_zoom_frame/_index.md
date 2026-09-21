---
title: add_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
새로운 Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다.

### 반환값

새로 생성된 [`IZoomFrame`](/slides/python-net/ko/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **float** | 새로운 Zoom 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새로운 Zoom 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새로운 Zoom 프레임의 너비(포인트 단위). |
| height | **float** | 새로운 Zoom 프레임의 높이(포인트 단위). |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | Zoom 프레임이 참조하는 [`ISlide`](/slides/python-net/ko/aspose.slides/islide); 이 프레젠테이션에 속해야 합니다. |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 참조된 슬라이드가 현재 프레젠테이션에 속하지 않을 경우 발생합니다. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
새로운 Zoom 프레임을 생성하고 도형 컬렉션의 끝에 추가합니다.

### 반환값

새로 생성된 [`IZoomFrame`](/slides/python-net/ko/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **float** | 새로운 Zoom 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새로운 Zoom 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새로운 Zoom 프레임의 너비(포인트 단위). |
| height | **float** | 새로운 Zoom 프레임의 높이(포인트 단위). |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | Zoom 프레임이 참조하는 [`ISlide`](/slides/python-net/ko/aspose.slides/islide); 이 프레젠테이션에 속해야 합니다. |
| image | [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage) | 참조된 슬라이드 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage)에 대한 이미지. |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 참조된 슬라이드가 현재 프레젠테이션에 속하지 않을 경우 발생합니다. |



### 참고
* 클래스 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 클래스 [`IZoomFrame`](/slides/python-net/ko/aspose.slides/izoomframe)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)