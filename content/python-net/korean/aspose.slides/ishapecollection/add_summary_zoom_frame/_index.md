---
title: add_summary_zoom_frame method
second_title: Aspose.Slides Python용 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
새 Summary Zoom 프레임을 생성하고 shape 컬렉션의 끝에 추가합니다.

### 반환

새로 생성된 [`ISummaryZoomFrame`](/slides/python-net/ko/aspose.slides/isummaryzoomframe).

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | **float** | 새 Summary Zoom 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 Summary Zoom 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 Summary Zoom 프레임의 너비(포인트 단위). |
| height | **float** | 새 Summary Zoom 프레임의 높이(포인트 단위). |

### 비고

이 메서드는 프레젠테이션의 모든 섹션에 대한 summary 링크를 집계하는 Summary Zoom 프레임을 생성합니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 프레젠테이션에 섹션이 없거나 대상 슬라이드가 어떤 섹션에도 속하지 않을 경우 발생합니다. |

### 참고
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 클래스 [`ISummaryZoomFrame`](/slides/python-net/ko/aspose.slides/isummaryzoomframe)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)