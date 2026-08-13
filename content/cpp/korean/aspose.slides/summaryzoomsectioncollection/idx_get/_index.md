---
title: idx_get()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 ISummaryZoomSection.
type: docs
weight: 40
url: /ko/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) 메서드

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## 비고

예제에서는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISummaryZoomSection](../../isummaryzoomsection/)
* 클래스 [SummaryZoomSectionCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)