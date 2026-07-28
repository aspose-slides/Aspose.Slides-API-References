---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca wszystkie ramki tekstowe na określonym slajdzie, które zawierają podany tekst.
type: docs
weight: 66
url: /pl/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) metoda

Zwraca wszystkie ramki tekstowe na określonym slajdzie, które zawierają podany tekst.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Slajd do przeszukania. |
| text | [System::String](../../../system/string/) | Tekst do wyszukania w ramkach tekstowych. |
| checkPlaceholderText | **bool** | Określa, czy uwzględnić ramki tekstowe, które są puste, ale ich tekst zastępczy zawiera szukany tekst. |

### Wartość zwracana

Tablica obiektów [ITextFrame](../../../aspose.slides/itextframe/), które zawierają określony tekst.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ITextFrame](../../../aspose.slides/itextframe/)
* Klasa [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Klasa [String](../../../system/string/)
* Klasa [SlideUtil](../)
* Przestrzeń nazw [Aspose::Slides::Util](../../)
* Biblioteka [Aspose.Slides](../../../)