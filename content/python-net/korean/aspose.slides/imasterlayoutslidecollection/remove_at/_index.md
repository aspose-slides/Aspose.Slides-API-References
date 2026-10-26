---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

```python
def remove_at(self, index):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 제거할 요소의 0부터 시작하는 인덱스입니다. |

### 비고

1) PptxEditException이 발생하지 않도록 먼저 layout의 HasDependingSlides 속성을 확인하십시오.  
2) 코드를 간소화하기 위해 [`ILayoutSlide.remove`](/slides/python-net/ko/aspose.slides/ilayoutslide/remove) 메서드를 사용할 수도 있습니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 프레젠테이션에서 레이아웃이 사용된 경우(HasDependingSlides 속성이 true인 경우) 발생합니다. |

### 참조
* 클래스 [`IMasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)