---
title: Add()
second_title: Aspose.Slides C++ API referencia
description: Új elrendezési diát ad a gyűjtemény végéhez.
type: docs
weight: 27
url: /hu/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) metódus

Új elrendezési diát ad a gyűjtemény végéhez.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Új elrendezés típusához. Támogatott elrendezési típusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Egyéb elrendezési típusok jelenleg nem támogatottak: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null paraméter kerül átadásra, akkor a név automatikusan generálódik a megadott elrendezési típus alapján (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

### Visszatérési érték

Hozzáadott dia.

## Megjegyzések

1) A(z) [SlideLayoutType::Custom](../../slidelayouttype/) értékhez hozzáadott elrendezés a *layoutType* paraméterhez nem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a metódusnak az analógja a [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) metódus, amely a [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) tulajdonsággal érhető el.

## Lásd még

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)