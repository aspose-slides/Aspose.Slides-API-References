---
title: Insert()
second_title: Aspose.Slides C++ API-referencia
description: Új elrendezési diát szúr be a gyűjtemény megadott pozíciójába.
type: docs
weight: 40
url: /hu/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metódus


Új elrendezési diát szúr be a gyűjtemény meghatározott pozíciójába.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Az új elrendezés típusához tartozó elrendezés típus. Támogatott elrendezés típusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jelenleg nem támogatott elrendezés típusok: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null paramétert adunk meg, akkor a név automatikusan generálódik a megadott elrendezés típus alapján (például \"Title Slide\" vagy \"1_Title Slide\", \"2_..\", stb.). |

### Visszatérési érték

Beszúrt dia.

## Megjegyzések

A(z) [SlideLayoutType::Custom](../../slidelayouttype/) értékű *layoutType* elrendezés beszúrása nem tartalmaz helyőrzőket és alakzatokat. 

## Lásd még

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)