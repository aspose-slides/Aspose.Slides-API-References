---
title: Insert()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vloží nový snímek rozvržení na určenou pozici ve sbírce.
type: docs
weight: 40
url: /cs/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metoda

Vloží novou layout slide na určenou pozici ve sbírce.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ layoutu pro novou layout. Podporované typy layoutu: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy layoutu nyní nejsou podporovány: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Název pro novou layout. Pokud je zadaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název vygenerován automaticky podle zadaného typu layoutu (například „Title Slide“ nebo „1_Title Slide“, „2_..“, atd.). |

### Návratová hodnota

Vložený snímek.

## Poznámky

Vložená layout pro hodnotu [SlideLayoutType::Custom](../../slidelayouttype/) typu *layoutType* neobsahuje žádné zástupce ani tvary. 

## Viz také

* Výčtový typ [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [String](../../../system/string/)
* Třída [IMasterLayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)