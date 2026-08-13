---
title: AddSummaryZoomSection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 Summary Zoom Section 객체를 생성하고 컬렉션에 추가합니다
type: docs
weight: 53
url: /ko/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) method

새로운 Summary Zoom [Section](../../section/) 객체를 생성하고 컬렉션에 추가합니다.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 새로운 Summary Zoom [Section](../../section/) 요소 [ISection](../../isection/) |

### 반환값

추가된 [ISummaryZoomFrame](../../isummaryzoomframe/) 요소

## 비고

컬렉션에 이 섹션에 대한 요소가 이미 존재하는 경우, 기존 요소가 반환됩니다.

예제는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISummaryZoomSection](../../isummaryzoomsection/)
* 클래스 [ISection](../../isection/)
* 클래스 [SummaryZoomSectionCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)