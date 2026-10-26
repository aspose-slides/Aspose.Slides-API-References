---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API 참조
description: Summary Zoom Frame 객체에 대한 ISummaryZoomSectionCollection을 가져옵니다.
type: docs
weight: 14
url: /ko/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() 메서드

[ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)를 Summary Zoom Frame 객체에 대해 가져옵니다.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## 비고

예제에서는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다:

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Class [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)