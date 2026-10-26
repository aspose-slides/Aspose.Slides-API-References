---
title: highlight_text method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/textframe/highlight_text/
weight: 20
---
## highlight_text(self, text, highlight_color) {#str-asposeslidescolor}
지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.

```python
def highlight_text(self, text, highlight_color):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | **str** | 강조할 텍스트 샘플. |
| highlight_color | [`Color`](/slides/python-net/ko/aspose.slides/color) | 텍스트를 강조 표시할 색상. |

## highlight_text(self, text, highlight_color, options) {#str-asposeslidescolor-itexthighlightingoptions}
지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.

```python
def highlight_text(self, text, highlight_color, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | **str** | 강조할 텍스트. |
| highlight_color | [`Color`](/slides/python-net/ko/aspose.slides/color) | 텍스트를 강조 표시할 색상. |
| options | [`ITextHighlightingOptions`](/slides/python-net/ko/aspose.slides/itexthighlightingoptions) | 강조 옵션. |

## highlight_text(self, text, highlight_color, options, callback) {#str-asposeslidescolor-itextsearchoptions-ifindresultcallback}
지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조 표시합니다.

```python
def highlight_text(self, text, highlight_color, options, callback):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | **str** | 강조할 텍스트. |
| highlight_color | [`Color`](/slides/python-net/ko/aspose.slides/color) | 텍스트를 강조 표시할 색상. |
| options | [`ITextSearchOptions`](/slides/python-net/ko/aspose.slides/itextsearchoptions) | 텍스트 검색 옵션 [`ITextSearchOptions`](/slides/python-net/ko/aspose.slides/itextsearchoptions). |
| callback | [`IFindResultCallback`](/slides/python-net/ko/aspose.slides/ifindresultcallback) | 검색 결과를 수신하기 위한 콜백 객체 [`IFindResultCallback`](/slides/python-net/ko/aspose.slides/ifindresultcallback). |

### 참고
* 클래스 [`IFindResultCallback`](/slides/python-net/ko/aspose.slides/ifindresultcallback)
* 클래스 [`ITextHighlightingOptions`](/slides/python-net/ko/aspose.slides/itexthighlightingoptions)
* 클래스 [`ITextSearchOptions`](/slides/python-net/ko/aspose.slides/itextsearchoptions)
* 클래스 [`TextFrame`](/slides/python-net/ko/aspose.slides/textframe)
* 클래스 [`Color`](/slides/python-net/ko/aspose.slides/color)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)