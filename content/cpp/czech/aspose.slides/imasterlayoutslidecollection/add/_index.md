---
title: Add()
second_title: Aspose.Slides pro C++ API referenci
description: Přidá nový snímek rozvržení na konec kolekce.
type: docs
weight: 27
url: /cs/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) metoda

Přidá nový snímek rozvržení na konec kolekce.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ rozvržení pro nové rozvržení. Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Další typy rozvržení nejsou v tuto chvíli podporovány: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Název pro nové rozvržení. Pokud je předaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název vygenerován automaticky na základě předaného typu rozvržení (například \"Title Slide\" nebo \"1_Title Slide\", \"2_..\", atd.). |

### Návratová hodnota

Přidaný snímek.

## Poznámky

1) Přidané rozvržení pro hodnotu [SlideLayoutType::Custom](../../slidelayouttype/) typu *layoutType* neobsahuje žádné zástupné symboly ani tvary. 2) Analogie této metody je metoda [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) přístupná přes vlastnost [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Viz také

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)