---
title: IndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 SummaryZoomSection 객체의 인덱스를 반환합니다.
type: docs
weight: 53
url: /ko/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) 메서드


지정된 [SummaryZoomSection](../../summaryzoomsection/) 개체의 인덱스를 반환합니다.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) 개체를 찾는 [ISummaryZoomSection](../../isummaryzoomsection/). |

### 반환값

[SummaryZoomSection](../../summaryzoomsection/) 개체의 인덱스 또는 이 컬렉션에 속하지 않는 [SummaryZoomSection](../../summaryzoomsection/) 개체인 경우 -1.

## 비고



예제는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISummaryZoomSection](../../isummaryzoomsection/)
* 클래스 [ISummaryZoomSectionCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)