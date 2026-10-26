---
title: Add()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Dodaje nowy slajd układu do prezentacji.
type: docs
weight: 14
url: /pl/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method


Dodaje nowy slajd układu do prezentacji.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Główny slajd dla nowego układu. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nazwa dla nowego układu. Jeśli podana nazwa jest już używana, zostanie wyrzucony ArgumentException. Jeśli przekazany zostanie parametr null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład \"Title Slide\" lub \"1_Title Slide\", \"2_..\", itp.). |

### Wartość zwracana

Dodany slajd.

## Uwagi

1) Dodany układ dla wartości [SlideLayoutType::Custom](../../slidelayouttype/) parametru *layoutType* nie zawiera żadnych symboli zastępczych ani kształtów. 2) Analogia tej metody to metoda [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) dostępna poprzez właściwość [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Zobacz także

* Wyliczenie [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [IMasterSlide](../../imasterslide/)
* Klasa [String](../../../system/string/)
* Klasa [IGlobalLayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)