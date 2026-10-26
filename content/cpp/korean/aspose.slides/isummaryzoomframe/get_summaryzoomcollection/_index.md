---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API 참조
description: Summary Zoom Frame 객체에 대한 ISummaryZoomSectionCollection을 가져옵니다.
type: docs
weight: 14
url: /ko/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() 메서드


Summary Zoom Frame 객체에 대한 [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)를 가져옵니다.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## 비고


예제에서는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* 클래스 [ISummaryZoomFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)