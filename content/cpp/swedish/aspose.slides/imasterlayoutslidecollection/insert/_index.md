---
title: Insert()
second_title: Aspose.Slides för C++ API-referens
description: Infogar en ny layoutbild på en angiven position i samlingen.
type: docs
weight: 40
url: /sv/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metod


Infogar en ny layoutbild på en angiven position i samlingen.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds inte för närvarande: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Namn för en ny layout. Om det angivna namnet redan är i bruk kommer ArgumentException att kastas. Om en null-parameter skickas genereras namnet automatiskt baserat på den angivna layouttypen (till exempel "Title Slide" eller "1_Title Slide", "2_..", osv.). |

### Returvärde

Infogad bild.

## Anmärkningar

Infogad layout för värdet [SlideLayoutType::Custom](../../slidelayouttype/) av *layoutType* innehåller inga platshållare och inga former. 

## Se också

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [ILayoutSlide](../../ilayoutslide/)
* klass [String](../../../system/string/)
* klass [IMasterLayoutSlideCollection](../)
* namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)