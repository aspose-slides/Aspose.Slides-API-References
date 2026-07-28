---
title: get_ColumnGapRule()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być ems lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)"
type: docs
weight: 105
url: /pl/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() metoda


Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być ems lub punktami (przechowywane jako twips). Domyślnie: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## Uwagi


Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zobacz także

* Wyliczenie [MathSpacingRules](../../mathspacingrules/)
* Klasa [MathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)