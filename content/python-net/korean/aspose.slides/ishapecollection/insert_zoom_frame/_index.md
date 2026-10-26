---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
새로운 Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환
새로 생성된 [`IZoomFrame`](/slides/python-net/ko/aspose.slides/izoomframe).

```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | Zoom 프레임을 삽입할 0 기반 index. |
| x | **float** | 새로운 Zoom 프레임의 x좌표(포인트 단위). |
| y | **float** | 새로운 Zoom 프레임의 y좌표(포인트 단위). |
| width | **float** | 새로운 Zoom 프레임의 너비(포인트 단위). |
| height | **float** | 새로운 Zoom 프레임의 높이(포인트 단위). |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | Zoom 프레임이 참조하는 [`ISlide`](/slides/python-net/ko/aspose.slides/islide). |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 참조된 slide가 현재 프레젠테이션에 포함되지 않은 경우 발생합니다. |

## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
미리 정의된 이미지를 사용하여 새로운 Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환
새로 생성된 [`IZoomFrame`](/slides/python-net/ko/aspose.slides/izoomframe).

```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | Zoom 프레임을 삽입할 0 기반 index. |
| x | **float** | 새로운 Zoom 프레임의 x좌표(포인트 단위). |
| y | **float** | 새로운 Zoom 프레임의 y좌표(포인트 단위). |
| width | **float** | 새로운 Zoom 프레임의 너비(포인트 단위). |
| height | **float** | 새로운 Zoom 프레임의 높이(포인트 단위). |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | Zoom 프레임이 참조하는 [`ISlide`](/slides/python-net/ko/aspose.slides/islide). |
| image | [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage) | Zoom 프레임이 참조하는 슬라이드 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage)에 대한 이미지. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 참조된 slide가 현재 프레젠테이션에 포함되지 않은 경우 발생합니다. |

### 참조
* 클래스 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 클래스 [`IZoomFrame`](/slides/python-net/ko/aspose.slides/izoomframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)