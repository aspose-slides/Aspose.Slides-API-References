---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
새 Summary Zoom 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환값

새로 생성된 [`ISummaryZoomFrame`](/slides/python-net/ko/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | Summary Zoom 프레임을 삽입할 0 기반 인덱스입니다. |
| x | **float** | 새 Summary Zoom 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 새 Summary Zoom 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 새 Summary Zoom 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 새 Summary Zoom 프레임의 높이이며, 단위는 포인트입니다. |

### 비고

이 메서드는 프레젠테이션의 모든 섹션에 대한 요약 링크를 집계하는 Summary Zoom 프레임을 생성합니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 프레젠테이션에 섹션이 없거나 대상 슬라이드가 어떤 섹션에도 속하지 않을 경우 발생합니다. |



### 참조
* 클래스 [`ISummaryZoomFrame`](/slides/python-net/ko/aspose.slides/isummaryzoomframe)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)