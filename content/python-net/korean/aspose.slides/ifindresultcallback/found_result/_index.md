---
title: found_result method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ifindresultcallback/found_result/
weight: 10
---
## found_result(self, text_frame, source_text, found_text, text_position) {#itextframe-str-str-int}
찾은 텍스트에 대한 데이터를 수신하는 콜백 메서드입니다.

```python
def found_result(self, text_frame, source_text, found_text, text_position):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text_frame | [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe) | 텍스트가 발견된 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| source_text | **str** | 텍스트가 발견된 원본 텍스트. |
| found_text | **str** | 검색된 텍스트. |
| text_position | **int** | 검색된 텍스트의 위치. |

### 참조
* 클래스 [`IFindResultCallback`](/slides/python-net/ko/aspose.slides/ifindresultcallback)
* 클래스 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)