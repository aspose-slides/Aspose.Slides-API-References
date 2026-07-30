---
title: Add()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá nový snímek rozvržení na konec kolekce.
type: docs
weight: 27
url: /cs/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) metoda

Přidá nový snímek rozvržení na konec kolekce.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ rozvržení pro nové rozvržení. Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozvržení nejsou momentálně podporovány: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Název pro nové rozvržení. Pokud je předaný název již používán, bude vyhozena výjimka ArgumentException. Pokud je předán parametr null, bude název vygenerován automaticky podle předaného typu rozvržení (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

### Návratová hodnota

Přidaný snímek.

## Poznámky

1) Přidané rozvržení pro hodnotu [SlideLayoutType::Custom](../../slidelayouttype/) typu *layoutType* neobsahuje žádné zástupné znaky ani tvary. 2) Analogie této metody je metoda [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) přístupná pomocí vlastnosti [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Viz také

* Výčet [SlideLayoutType](../../slidelayouttype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [String](../../../system/string/)
* Třída [MasterLayoutSlideCollection](../)
* Obor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)