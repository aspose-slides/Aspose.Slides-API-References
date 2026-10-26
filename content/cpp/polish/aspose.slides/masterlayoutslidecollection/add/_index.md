---
title: Add()
second_title: Referencja API Aspose.Slides dla C++
description: Dodaje nowy slajd układu na koniec kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) metoda

Dodaje nowy slajd układu na koniec kolekcji.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nazwa nowego układu. Jeśli podana nazwa jest już w użyciu, zostanie wyrzucony ArgumentException. Jeśli przekazany zostanie parametr null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład \"Title Slide\" lub \"1_Title Slide\", \"2_..\", itp.). |

### Wartość zwracana

Dodany slajd.

## Uwagi

1) Dodano układ dla wartości [SlideLayoutType::Custom](../../slidelayouttype/) typu *layoutType* nie zawiera żadnych znaczników i żadnych kształtów. 2) Analogia tej metody to metoda [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) dostępna za pośrednictwem własności [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Zobacz także

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [String](../../../system/string/)
* Klasa [MasterLayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)