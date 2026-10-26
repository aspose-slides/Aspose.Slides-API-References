---
title: remove_at method
second_title: Aspose.Slides Python용 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masterslidecollection/remove_at/
weight: 40
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

PptxEditException이 발생하는 것을 방지하려면 마스터의 HasDependingSlides 속성을 먼저 확인하십시오.

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 마스터를 제거하려는 경우 해당 마스터가 프레젠테이션에서 사용 중이며(HasDependingSlides 속성이 true) 예외가 발생합니다. |

### 또한 보기
* 클래스 [`MasterSlideCollection`](/slides/python-net/ko/aspose.slides/masterslidecollection)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)