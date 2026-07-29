---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny layoutbild i presentationen.
type: docs
weight: 14
url: /sv/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) metod

Lägger till ett nytt layoutbild i presentationen.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterbild för ett nytt layout. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layouttyp för ett nytt layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds inte för närvarande: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Namn för ett nytt layout. Om det angivna namnet redan används kastas ArgumentException. Om null-parameter skickas genereras namnet automatiskt utifrån den angivna layouttypen (till exempel \"Title Slide\" eller \"1_Title Slide\", \"2_..\", osv.). |

### Returvärde

Tillagd bild.

## Anmärkningar

1) Tillagt layout för värdet [SlideLayoutType::Custom](../../slidelayouttype/) av *layoutType* innehåller inga platshållare och inga former. 2) Motsvarigheten till denna metod är metod [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) som nås via egenskapen [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Se även

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [IMasterSlide](../../imasterslide/)
* Klass [String](../../../system/string/)
* Klass [IGlobalLayoutSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)