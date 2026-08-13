---
title: Insert()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션의 지정된 위치에 새 레이아웃 슬라이드를 삽입합니다.
type: docs
weight: 40
url: /ko/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) 메서드

새 레이아웃 슬라이드를 컬렉션의 지정된 위치에 삽입합니다.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 새 슬라이드의 인덱스. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 새 레이아웃의 레이아웃 유형. 지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 새 레이아웃의 이름. 전달된 이름이 이미 사용 중인 경우 ArgumentException이 발생합니다. null 매개변수가 전달되면 전달된 레이아웃 유형에 따라 이름이 자동으로 생성됩니다(예: "Title Slide" 또는 "1_Title Slide", "2_..", 등). |

### 반환값

삽입된 슬라이드.

## 비고

[SlideLayoutType::Custom](../../slidelayouttype/) 값의 *layoutType*에 대한 삽입된 레이아웃에는 플레이스홀더와 도형이 없습니다. 

## 참조

* 열거형 [SlideLayoutType](../../slidelayouttype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [String](../../../system/string/)
* 클래스 [IMasterLayoutSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)