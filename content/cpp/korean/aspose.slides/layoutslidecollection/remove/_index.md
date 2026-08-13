---
title: Remove()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 레이아웃을 제거합니다.
type: docs
weight: 66
url: /ko/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) 메서드

컬렉션에서 레이아웃을 제거합니다.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 컬렉션에서 제거할 레이아웃 슬라이드입니다. |
## 비고

1) PptxEditException이 발생하는 것을 방지하려면 layout의 HasDependingSlides 속성을 먼저 확인하십시오. 2) 코드를 간소화하려면 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 메서드를 사용할 수도 있습니다. 
## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [LayoutSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)