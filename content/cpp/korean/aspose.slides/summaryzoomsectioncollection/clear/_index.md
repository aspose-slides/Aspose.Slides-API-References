---
title: Clear()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 모든 SummaryZoomSection 객체를 제거합니다.
type: docs
weight: 105
url: /ko/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() 메서드

컬렉션에서 모든 [SummaryZoomSection](../../summaryzoomsection/) 객체를 제거합니다.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## 비고

이 예제는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 것을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## 참고

* 클래스 [SummaryZoomSectionCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)