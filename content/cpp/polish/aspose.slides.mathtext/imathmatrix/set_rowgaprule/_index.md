---
title: set_RowGapRule()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być wierszami lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)"
type: docs
weight: 170
url: /pl/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) metoda

Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być wierszami lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## Uwagi

Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zobacz także

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)