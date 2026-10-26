---
title: Remove()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 레이아웃을 제거합니다.
type: docs
weight: 27
url: /ko/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) method

컬렉션에서 레이아웃을 제거합니다.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 컬렉션에서 제거할 레이아웃 슬라이드. |
## 비고

1) PptxEditException이 발생하는 것을 방지하려면 레이아웃의 HasDependingSlides 속성을 먼저 확인하십시오. 2) 또한 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 메서드를 사용하여 코드를 단순화할 수 있습니다. 
## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [ILayoutSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)