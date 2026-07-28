---
title: Add()
second_title: Aspose.Slides dla C++ Referencja API
description: Dodaje nowy slajd układu do prezentacji.
type: docs
weight: 14
url: /pl/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) metoda


Dodaje nowy slajd układu do prezentacji.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Główny slajd dla nowego układu. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nazwa dla nowego układu. Jeśli podana nazwa jest już używana, zostanie rzucony ArgumentException. Jeśli przekazany parametr jest null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład "Title Slide" lub "1_Title Slide", "2_..", itp.). |

### Wartość zwracana

Dodany slajd.

## Uwagi

1) Dodany układ dla wartości [SlideLayoutType::Custom](../../slidelayouttype/) typu *layoutType* nie zawiera symboli zastępczych ani kształtów. 2) Analogie tej metody jest metoda [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) dostępna za pomocą właściwości [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 

## Zobacz także

* Wyliczenie [SlideLayoutType](../../slidelayouttype/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [IMasterSlide](../../imasterslide/)
* Klasa [String](../../../system/string/)
* Klasa [GlobalLayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)