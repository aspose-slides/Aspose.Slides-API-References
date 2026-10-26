---
title: Add()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dodaje nowy slajd układu na koniec kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) metoda

Dodaje nowy slajd układu na koniec kolekcji.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie wyrzucony ArgumentException. Jeśli przekazany parametr jest null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład „Title Slide” lub „1_Title Slide”, „2_..”, itp.). |

### Wartość zwracana

Dodany slajd.

## Uwagi

1) Dodany układ dla wartości [SlideLayoutType::Custom](../../slidelayouttype/) *layoutType* nie zawiera żadnych pól zastępczych ani kształtów. 2) Odpowiednikiem tej metody jest metoda [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) dostępna za pomocą właściwości [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Zobacz także

* Wyliczenie [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [String](../../../system/string/)
* Klasa [IMasterLayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)