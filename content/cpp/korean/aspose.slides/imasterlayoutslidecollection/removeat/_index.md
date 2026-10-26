---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.
type: docs
weight: 53
url: /ko/aspose.slides/imasterlayoutslidecollection/removeat/
---
## IMasterLayoutSlideCollection::RemoveAt(int32_t) 메서드

컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

```cpp
virtual void Aspose::Slides::IMasterLayoutSlideCollection::RemoveAt(int32_t index)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 제거할 요소의 0부터 시작하는 인덱스입니다. |
## 비고

1) PptxEditException이 발생하는 것을 방지하려면 레이아웃의 HasDependingSlides 속성을 미리 확인하십시오. 2) 코드를 단순화하기 위해 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 메서드를 사용할 수도 있습니다.
## 참조

* 클래스 [IMasterLayoutSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)