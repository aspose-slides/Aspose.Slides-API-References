---
title: GetSummarySection()
second_title: Aspose.Slides for C++ API 참조
description: 주어진 섹션에 대한 Summary Zoom Section 요소를 반환합니다.
type: docs
weight: 92
url: /ko/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) 메서드


주어진 섹션에 대한 Summary Zoom [Section](../../section/) 요소를 반환합니다.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/)를 찾아 [ISection](../../isection/) |

### 반환 값

[ISummaryZoomSection](../../isummaryzoomsection/) 또는 컬렉션에 해당 섹션의 요소가 없으면 null을 반환합니다.

## 비고



예제는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## 또 다른 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISummaryZoomSection](../../isummaryzoomsection/)
* 클래스 [ISection](../../isection/)
* 클래스 [SummaryZoomSectionCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)