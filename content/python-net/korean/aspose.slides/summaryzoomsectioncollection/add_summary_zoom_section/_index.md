---
title: add_summary_zoom_section method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
새 Summary Zoom Section 객체를 생성하고 컬렉션에 추가합니다

### 반환값

[`ISummaryZoomFrame`](/slides/python-net/ko/aspose.slides/isummaryzoomframe) 요소가 추가되었습니다



```python
def add_summary_zoom_section(self, section):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/ko/aspose.slides/isection) | 새 Summary Zoom Section 요소를 위한 섹션 [`ISection`](/slides/python-net/ko/aspose.slides/isection) |

### 비고

컬렉션에 해당 섹션의 요소가 이미 존재하면 기존 요소가 반환됩니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 참조된 섹션이 현재 프레젠테이션에 속하지 않거나 슬라이드가 포함되어 있지 않습니다. |



### 참조
* 클래스 [`ISection`](/slides/python-net/ko/aspose.slides/isection)
* 클래스 [`ISummaryZoomFrame`](/slides/python-net/ko/aspose.slides/isummaryzoomframe)
* 클래스 [`ISummaryZoomSection`](/slides/python-net/ko/aspose.slides/isummaryzoomsection)
* 클래스 [`SummaryZoomSectionCollection`](/slides/python-net/ko/aspose.slides/summaryzoomsectioncollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)