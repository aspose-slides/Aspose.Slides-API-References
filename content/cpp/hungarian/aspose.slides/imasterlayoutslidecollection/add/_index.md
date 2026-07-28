---
title: Add()
second_title: Aspose.Slides C++ API referencia
description: Új elrendezésdia hozzáadása a gyűjtemény végéhez.
type: docs
weight: 27
url: /hu/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) method

Új elrendezésdia hozzáadása a gyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Az új elrendezés típusa. Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. A többi elrendezéstípus jelenleg nem támogatott: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException kerül dobásra. Ha null paraméter kerül átadásra, akkor a név automatikusan generálódik a megadott elrendezéstípus alapján (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

### Visszatérési érték

Hozzáadott dia.

## Megjegyzések

1) A [SlideLayoutType::Custom](../../slidelayouttype/) értékhez hozzáadott elrendezés a *layoutType* esetén nem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a metódusnak analógja a [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) metódus, amely a [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) tulajdonsággal érhető el.

## Lásd még

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)