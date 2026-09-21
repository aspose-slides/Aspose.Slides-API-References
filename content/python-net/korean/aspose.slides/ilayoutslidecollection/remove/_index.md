---
title: remove method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
컬렉션에서 레이아웃을 제거합니다.

```python
def remove(self, value):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide) | 컬렉션에서 제거할 레이아웃 슬라이드입니다. |

### 비고

1) PptxEditException이 발생하는 것을 방지하려면 레이아웃의 HasDependingSlides 속성을 먼저 확인하십시오.
2) 코드를 단순화하기 위해 [`ILayoutSlide.remove`](/slides/python-net/ko/aspose.slides/ilayoutslide/remove) 메서드를 사용할 수도 있습니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 프레젠테이션에서 레이아웃이 사용된 경우 발생합니다(HasDependingSlides 속성이 true인 경우). |

### 참조
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`ILayoutSlideCollection`](/slides/python-net/ko/aspose.slides/ilayoutslidecollection)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)