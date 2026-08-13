---
title: AddSummaryZoomSection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 Summary Zoom Section 객체를 생성하고 컬렉션에 추가합니다
type: docs
weight: 14
url: /ko/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) 메서드

새로운 Summary Zoom [Section](../../section/) 개체를 생성하고 컬렉션에 추가합니다

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 새로운 Summary Zoom [Section](../../section/) 요소를 위한 [ISection](../../isection/) |

### 반환값

추가된 [ISummaryZoomFrame](../../isummaryzoomframe/) 요소

## 비고

컬렉션에 이미 이 섹션에 대한 요소가 존재한다면, 기존 요소가 반환됩니다. 

예제는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)