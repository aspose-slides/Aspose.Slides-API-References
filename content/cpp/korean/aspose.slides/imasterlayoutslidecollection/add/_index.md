---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 레이아웃 슬라이드를 컬렉션의 끝에 추가합니다.
type: docs
weight: 27
url: /ko/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) 메서드

새 레이아웃 슬라이드를 컬렉션 끝에 추가합니다.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 새 레이아웃의 레이아웃 유형. 지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 다른 레이아웃 유형은 현재 지원되지 않습니다: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 새 레이아웃의 이름. 전달된 이름이 이미 사용 중인 경우 ArgumentException이 발생합니다. null 매개변수가 전달되면 전달된 레이아웃 유형에 따라 이름이 자동으로 생성됩니다(예: "Title Slide" 또는 "1_Title Slide", "2_..", 등). |

### 반환 값

추가된 슬라이드.

## 비고

1) 값 [SlideLayoutType::Custom](../../slidelayouttype/)의 *layoutType*에 대한 레이아웃이 추가되었습니다. 자리표시자가 없으며 도형도 없습니다. 2) 이 메서드와 유사한 메서드는 [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/)이며, [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) 속성을 통해 액세스됩니다.

## 참고

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)