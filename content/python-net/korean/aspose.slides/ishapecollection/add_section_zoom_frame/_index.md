---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
새 Section Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

### 반환값

새로 생성된 [`ISectionZoomFrame`](/slides/python-net/ko/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | **float** | 새 Section Zoom 프레임의 x 좌표(포인트). |
| y | **float** | 새 Section Zoom 프레임의 y 좌표(포인트). |
| width | **float** | 새 Section Zoom 프레임의 너비(포인트). |
| height | **float** | 새 Section Zoom 프레임의 높이(포인트). |
| section | [`ISection`](/slides/python-net/ko/aspose.slides/isection) | Section Zoom 프레임이 참조하는 [`ISection`](/slides/python-net/ko/aspose.slides/isection); <br/><br/> 이 프레젠테이션에 속하고 최소 하나의 슬라이드가 있어야 합니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 참조된 섹션이 현재 프레젠테이션에 속하지 않거나 슬라이드가 없는 경우 발생합니다. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
기본 이미지가 정의된 새 Section Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

### 반환값

새로 생성된 [`ISectionZoomFrame`](/slides/python-net/ko/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | **float** | 새 Section Zoom 프레임의 x 좌표(포인트). |
| y | **float** | 새 Section Zoom 프레임의 y 좌표(포인트). |
| width | **float** | 새 Section Zoom 프레임의 너비(포인트). |
| height | **float** | 새 Section Zoom 프레임의 높이(포인트). |
| section | [`ISection`](/slides/python-net/ko/aspose.slides/isection) | Section Zoom 프레임이 참조하는 [`ISection`](/slides/python-net/ko/aspose.slides/isection); <br/><br/> 이 프레젠테이션에 속하고 최소 하나의 슬라이드가 있어야 합니다. |
| image | [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage) | Section Zoom 프레임 내에 표시되는 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage). |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 참조된 섹션이 현재 프레젠테이션에 속하지 않거나 슬라이드가 없는 경우 발생합니다. |



### 참조
* 클래스 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage)
* 클래스 [`ISection`](/slides/python-net/ko/aspose.slides/isection)
* 클래스 [`ISectionZoomFrame`](/slides/python-net/ko/aspose.slides/isectionzoomframe)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)