---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny layoutbild i slutet av samlingen.
type: docs
weight: 27
url: /sv/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) metod

Lägger till en ny layout-bild i slutet av samlingen.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layouttyp för ett nytt layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds för närvarande inte: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Namn för ett nytt layout. Om det angivna namnet redan är i bruk kastas en ArgumentException. Om en null-parameter skickas genereras namnet automatiskt utifrån den angivna layouttypen (till exempel "Title Slide" eller "1_Title Slide", "2_..", etc.). |

### Returvärde

Tillagd bild.

## Anmärkningar

1) Tillagt layout för värdet [SlideLayoutType::Custom](../../slidelayouttype/) av *layoutType* innehåller inga platshållare och inga former. 2) Motsvarigheten till denna metod är metod [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) som nås via egenskapen [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Se även

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [String](../../../system/string/)
* Klass [MasterLayoutSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)