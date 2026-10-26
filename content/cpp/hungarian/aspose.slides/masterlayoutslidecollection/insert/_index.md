---
title: Insert()
second_title: Aspose.Slides C++ API referencia
description: Új elrendezési diát szúr be a gyűjtemény megadott pozíciójába.
type: docs
weight: 40
url: /hu/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metódus


Beszúr egy új elrendezési diát a gyűjtemény megadott pozíciójába.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új diának az indexe. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Az új elrendezéshez használt elrendezéstípus. Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Más elrendezéstípusok jelenleg nem támogatottak: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null paramétert adnak meg, akkor a név automatikusan lesz generálva a megadott elrendezéstípus alapján (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

### Visszatérési érték

Beszúrt dia.

## Megjegyzés

A(z) [SlideLayoutType::Custom](../../slidelayouttype/) értékű *layoutType* elrendezés beszúrása nem tartalmaz helyőrzőket és alakzatokat. 

## Lásd még

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)