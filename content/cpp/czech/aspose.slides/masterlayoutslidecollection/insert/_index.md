---
title: Insert()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vloží nový snímek rozvržení na určenou pozici v kolekci.
type: docs
weight: 40
url: /cs/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metoda

Vloží nový snímek rozvržení na zadanou pozici kolekce.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ rozvržení pro nové rozvržení. Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Další typy rozvržení nejsou momentálně podporovány: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Název nového rozvržení. Pokud je předaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název automaticky vygenerován na základě předaného typu rozvržení (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

### Návratová hodnota

Vložený snímek.

## Poznámky

Vložené rozvržení pro hodnotu [SlideLayoutType::Custom](../../slidelayouttype/) typu *layoutType* neobsahuje žádné zástupné symboly ani žádné tvary. 

## Viz také

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [String](../../../system/string/)
* Třída [MasterLayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)