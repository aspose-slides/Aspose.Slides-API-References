---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션에 새로운 레이아웃 슬라이드를 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) 메서드

프레젠테이션에 새로운 레이아웃 슬라이드를 추가합니다.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 새 레이아웃의 마스터 슬라이드. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 새 레이아웃의 레이아웃 유형. 지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 다른 레이아웃 유형은 현재 지원되지 않습니다: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 새 레이아웃의 이름. 전달된 이름이 이미 사용 중이면 ArgumentException이 발생합니다. null 파라미터가 전달되면 레이아웃 유형에 따라 이름이 자동으로 생성됩니다(예: "Title Slide" 또는 "1_Title Slide", "2_..", 등). |

### 반환 값

추가된 슬라이드.

## 비고

1) *layoutType* 값 [SlideLayoutType::Custom](../../slidelayouttype/)에 대한 추가된 레이아웃은 자리표시자와 도형이 없습니다. 2) 이 메서드와 대응되는 메서드는 [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/)이며, [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) 속성을 통해 액세스합니다.

## 또 보기

* 열거형 [SlideLayoutType](../../slidelayouttype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [IMasterSlide](../../imasterslide/)
* 클래스 [String](../../../system/string/)
* 클래스 [GlobalLayoutSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)