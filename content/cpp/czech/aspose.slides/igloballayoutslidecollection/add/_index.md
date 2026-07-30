---
title: Add()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Přidá nový snímek rozvržení do prezentace.
type: docs
weight: 14
url: /cs/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method

Přidá nový snímek rozvržení do prezentace.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Hlavní snímek pro nové rozvržení. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ rozvržení pro nové rozvržení. Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jiné typy rozvržení nyní nejsou podporovány: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Název pro nové rozvržení. Jestliže je předaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název vygenerován automaticky na základě předaného typu rozvržení (například \"Title Slide\" nebo \"1_Title Slide\", \"2_..\", atd.). |

### Return Value

Přidaný snímek.

## Remarks

1) Přidané rozvržení pro hodnotu [SlideLayoutType::Custom](../../slidelayouttype/) parametru *layoutType* neobsahuje žádné zástupné symboly ani žádné tvary. 2) Analogie této metody je metoda [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) přístupná přes vlastnost [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## See Also

* Výčet [SlideLayoutType](../../slidelayouttype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [IMasterSlide](../../imasterslide/)
* Třída [String](../../../system/string/)
* Třída [IGlobalLayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)