---
title: get_BaseJustification()
second_title: Aspose.Slides dla C++: odniesienie API
description: "Określa pionowe wyrównanie względem otaczającego tekstu. Dopuszczalne wartości to top, bottom i center. Domyślnie: Center"
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() metoda

Określa pionowe wyrównanie względem otaczającego tekstu. Dopuszczalne wartości to top, bottom i center. Domyślnie: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Uwagi

Przykład:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Zobacz także

* Wyliczenie [MathVerticalAlignment](../../mathverticalalignment/)
* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)