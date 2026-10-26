---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
지정된 슬라이드에서 지정된 텍스트를 포함하는 모든 텍스트 프레임을 반환합니다.

### 반환

[`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe) 객체 배열로, 지정된 텍스트를 포함합니다.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide) | 검색할 슬라이드입니다. |
| text | **str** | 텍스트 프레임 내에서 검색할 텍스트입니다. |
| check_placeholder_text | **bool** | 플레이스홀더 텍스트에 검색 텍스트가 포함되어 있지만 비어있는 텍스트 프레임을 포함할지 여부를 나타냅니다. |



### 관련 항목
* 클래스 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide)
* 클래스 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe)
* 클래스 [`SlideUtil`](/slides/python-net/ko/aspose.slides.util/slideutil)
* 모듈 [`aspose.slides.util`](/slides/python-net/ko/aspose.slides.util)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)