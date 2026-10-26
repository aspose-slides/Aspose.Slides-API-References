---
title: find_and_replace_text method
second_title: Python용 Aspose.Slides .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.util/slideutil/find_and_replace_text/
weight: 20
---
## find_and_replace_text(presentation, with_masters, find, replace, format) {#ipresentation-bool-str-str-portionformat}
프레젠테이션에서 텍스트를 찾고 지정된 형식으로 교체합니다


```python
@staticmethod
def find_and_replace_text(presentation, with_masters, find, replace, format):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) | 스캔된 프레젠테이션. |
| with_masters | **bool** | 마스터 슬라이드를 스캔할지 여부를 결정합니다. |
| find | **str** | 찾을 문자열 값. |
| replace | **str** | 교체할 문자열 값. |
| format | [`PortionFormat`](/slides/python-net/ko/aspose.slides/portionformat) | 텍스트 부분을 교체하기 위한 형식. None이면 찾은 문자열의 첫 번째 <br/><br/>            문자에 사용된 형식이 적용됩니다. |



### 참조
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 클래스 [`PortionFormat`](/slides/python-net/ko/aspose.slides/portionformat)
* 클래스 [`SlideUtil`](/slides/python-net/ko/aspose.slides.util/slideutil)
* 모듈 [`aspose.slides.util`](/slides/python-net/ko/aspose.slides.util)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)