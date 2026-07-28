---
title: get_RowGapRule()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być wierszami lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)"
type: docs
weight: 157
url: /pl/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() metoda

Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być wierszami lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## Uwagi

Przykład:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zobacz także

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)