---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 Summary Zoom Section 객체를 제거합니다.
type: docs
weight: 79
url: /ko/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) 메서드

컬렉션에서 Summary Zoom [Section](../../section/) 객체를 제거합니다.
```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/)에 대한 Summary Zoom [Section](../../section/) 요소를 제거하기 위한 [ISection](../../isection/). |
## 비고

예제에서는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISection](../../isection/)
* 클래스 [SummaryZoomSectionCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)