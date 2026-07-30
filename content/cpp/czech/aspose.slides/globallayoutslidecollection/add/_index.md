---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový snímek rozvržení do prezentace.
type: docs
weight: 14
url: /cs/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) metoda

Přidá nový snímek rozvržení do prezentace.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Hlavní snímek pro nové rozložení. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ rozložení pro nové rozložení. Podporované typy rozložení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozložení nejsou v současnosti podporovány: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Název nového rozložení. Pokud je předaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název generován automaticky na základě předaného typu rozložení (například \"Title Slide\" nebo \"1_Title Slide\", \"2_..\", atd.). |

### Návratová hodnota

Přidaný snímek.

## Poznámky

1) Přidané rozložení pro hodnotu [SlideLayoutType::Custom](../../slidelayouttype/) parametru *layoutType* neobsahuje žádné zástupné znaky ani tvary. 2) Analogie této metody je metoda [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) přístupná pomocí vlastnosti [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Viz také

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [IMasterSlide](../../imasterslide/)
* Třída [String](../../../system/string/)
* Třída [GlobalLayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)