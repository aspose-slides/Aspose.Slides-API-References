---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny layoutbild i slutet av samlingen.
type: docs
weight: 27
url: /sv/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) method


Adds a new layout slide to the end of the collection.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds inte för närvarande: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Namn för en ny layout. Om angivet namn redan används kastas ArgumentException. Om null-parameter skickas genereras namn automatiskt med hänsyn till den angivna layouttypen (t.ex. "Title Slide" eller "1_Title Slide", "2_..", osv.). |

### Returvärde

Added slide.

## Anmärkningar

1) Tillagd layout för värdet [SlideLayoutType::Custom](../../slidelayouttype/) av *layoutType* innehåller inga platshållare och inga former. 2) Motsvarigheten till denna metod är metod [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) som nås via egenskapen [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Se även

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [String](../../../system/string/)
* Klass [IMasterLayoutSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)