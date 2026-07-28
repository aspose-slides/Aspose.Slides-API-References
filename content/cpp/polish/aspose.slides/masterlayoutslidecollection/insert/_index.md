---
title: Insert()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wstawia nowy slajd układu w określonej pozycji kolekcji.
type: docs
weight: 40
url: /pl/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metoda

Wstawia nowy slajd układu w określonej pozycji kolekcji.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie rzucony ArgumentException. Jeśli przekazany zostanie parametr null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład "Title Slide" lub "1_Title Slide", "2_..", itd.). |

### Return Value

Wstawiony slajd.

## Remarks

Wstawiony układ dla wartości [SlideLayoutType::Custom](../../slidelayouttype/) typu *layoutType* nie zawiera pól zastępczych ani kształtów.

## See Also

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [String](../../../system/string/)
* Klasa [MasterLayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)