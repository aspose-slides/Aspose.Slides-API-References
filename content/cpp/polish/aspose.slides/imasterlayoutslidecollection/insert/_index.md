---
title: Insert()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Wstawia nowy slajd układu w określonej pozycji kolekcji.
type: docs
weight: 40
url: /pl/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metoda

Wstawia nowy slajd układu w określonej pozycji kolekcji.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie rzucony ArgumentException. Jeśli przekazany parametr jest null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład \"Title Slide\" lub \"1_Title Slide\", \"2_..\", itp.). |

### Wartość zwracana

Wstawiony slajd.

## Uwagi

Wstawiony układ dla wartości [SlideLayoutType::Custom](../../slidelayouttype/) typu *layoutType* nie zawiera żadnych placeholderów ani kształtów.

## Zobacz także

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)