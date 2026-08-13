---
title: Insert()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션의 지정된 위치에 새 레이아웃 슬라이드를 삽입합니다.
type: docs
weight: 40
url: /ko/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) method


컬렉션의 지정된 위치에 새 레이아웃 슬라이드를 삽입합니다.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 슬라이드의 인덱스. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 새 레이아웃의 레이아웃 유형. 지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 새 레이아웃의 이름. 전달된 이름이 이미 사용 중이면 ArgumentException이 발생합니다. null 매개변수가 전달되면 전달된 레이아웃 유형에 따라 이름이 자동으로 생성됩니다(예: \"Title Slide\" 또는 \"1_Title Slide\", \"2_..\" 등). |

### 반환 값

삽입된 슬라이드.

## 비고



값 [SlideLayoutType::Custom](../../slidelayouttype/)의 삽입된 레이아웃 *layoutType* 은 자리표시자와 도형이 없습니다. 

## 참조

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)