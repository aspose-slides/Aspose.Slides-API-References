---
title: set_ColumnGapRule()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być w em lub punktach (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)"
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) metoda


Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być w em lub punktach (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
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