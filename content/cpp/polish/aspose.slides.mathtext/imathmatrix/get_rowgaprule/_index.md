---
title: get_RowGapRule()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być liniami lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)"
type: docs
weight: 157
url: /pl/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() metoda


Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być liniami lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Uwagi


Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zobacz także

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)