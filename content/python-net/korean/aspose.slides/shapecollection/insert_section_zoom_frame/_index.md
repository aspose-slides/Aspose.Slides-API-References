---
title: insert_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
새 Section Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환값

The newly created [`ISectionZoomFrame`](/slides/python-net/ko/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | Section Zoom 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 Section Zoom 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 Section Zoom 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 Section Zoom 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 Section Zoom 프레임의 높이(포인트 단위)입니다. |
| section | [`ISection`](/slides/python-net/ko/aspose.slides/isection) | Section Zoom 프레임이 참조하는 [`ISection`](/slides/python-net/ko/aspose.slides/isection);<br/><br/>            이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 참조된 섹션이 현재 프레젠테이션에 속하지 않거나 슬라이드가 없을 경우 발생합니다. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
미리 정의된 이미지를 사용하여 새 Section Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환값

The newly created [`ISectionZoomFrame`](/slides/python-net/ko/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | Section Zoom 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 Section Zoom 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 Section Zoom 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 Section Zoom 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 Section Zoom 프레임의 높이(포인트 단위)입니다. |
| section | [`ISection`](/slides/python-net/ko/aspose.slides/isection) | Section Zoom 프레임이 참조하는 [`ISection`](/slides/python-net/ko/aspose.slides/isection);<br/><br/>            이 프레젠테이션에 속하고 최소 하나의 슬라이드를 포함해야 합니다. |
| image | [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage) | Section Zoom 프레임 내부에 표시할 이미지입니다. |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 참조된 섹션이 현재 프레젠테이션에 속하지 않거나 슬라이드가 없을 경우 발생합니다. |



### 또 보기
* 클래스 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage)
* 클래스 [`ISection`](/slides/python-net/ko/aspose.slides/isection)
* 클래스 [`ISectionZoomFrame`](/slides/python-net/ko/aspose.slides/isectionzoomframe)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)