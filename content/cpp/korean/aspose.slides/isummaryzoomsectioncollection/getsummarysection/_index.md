---
title: GetSummarySection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 주어진 섹션에 대한 Summary Zoom 섹션 요소를 반환합니다.
type: docs
weight: 27
url: /ko/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) 메서드


주어진 섹션에 대한 Summary Zoom [Section](../../section/) 요소를 반환합니다.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 찾기 위해 [ISection](../../isection/) |

### 반환 값

[ISummaryZoomSection](../../isummaryzoomsection/) 또는 null, 컬렉션에 섹션에 대한 요소가 포함되지 않은 경우.

## 비고



이 예제는 인덱스로 Summary Zoom [Section](../../section/) 요소를 가져오는 방법을 보여줍니다: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISummaryZoomSection](../../isummaryzoomsection/)
* 클래스 [ISection](../../isection/)
* 클래스 [ISummaryZoomSectionCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)