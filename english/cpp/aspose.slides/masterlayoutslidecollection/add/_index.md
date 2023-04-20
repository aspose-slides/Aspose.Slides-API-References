---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new layout slide to the end of the collection.
type: docs
weight: 27
url: /cpp/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) method


Adds a new layout slide to the end of the collection.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example \"Title Slide\" or \"1_Title Slide\", \"2_..\", etc.). |

### Return Value

Added slide.
## Remarks



1) Added layout for value [SlideLayoutType::Custom](../../slidelayouttype/) of *layoutType*  contains no placeholders and no shapes. 2) Analogue of this method is method [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) accessed with [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) property. 

## See Also

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)