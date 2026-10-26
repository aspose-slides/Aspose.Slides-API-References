---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny layoutbild i presentationen.
type: docs
weight: 14
url: /sv/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) metod


Lägger till en ny layoutbild i presentationen.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterbild för en ny layout. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds inte för tillfället: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Namn för en ny layout. Om det angivna namnet redan används kommer ArgumentException att kastas. Om null-parameter skickas genereras namnet automatiskt utifrån den angivna layouttypen (till exempel \"Title Slide\" eller \"1_Title Slide\", \"2_..\", etc.). |

### Returvärde

Tillagd bild.

## Anmärkningar

1) Tillagd layout för värdet [SlideLayoutType::Custom](../../slidelayouttype/) av *layoutType* innehåller inga platshållare och inga former. 2) Motsvarigheten till denna metod är metoden [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) som nås via egenskapen [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Se även

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [GlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)