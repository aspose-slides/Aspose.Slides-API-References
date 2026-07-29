---
title: Insert()
second_title: Aspose.Slides för C++ API-referens
description: Infogar en ny layout-bild på angiven position i samlingen.
type: docs
weight: 40
url: /sv/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metod


Infogar en ny layout-bild på angiven position i samlingen.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för ny bild. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds inte för närvarande: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Namn för en ny layout. Om det angivna namnet redan är i bruk kommer ArgumentException att kastas. Om en null-parameter ges genereras namnet automatiskt baserat på den angivna layouttypen (till exempel \"Title Slide\" eller \"1_Title Slide\", \"2_..\", osv.). |

### Returvärde

Infogad bild.
## Anmärkningar



Infogad layout för värdet [SlideLayoutType::Custom](../../slidelayouttype/) av *layoutType*  innehåller inga platshållare och inga former. 

## Se även

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [String](../../../system/string/)
* Klass [MasterLayoutSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)