---
title: set_ColumnGapRule()
second_title: Aspose.Slides dla C++ API Reference
description: "Typ poziomego odstępu między kolumnami macierzy; jednostki odstępu poziomego mogą być w em lub punktach (przechowywane jako twips). Domyślnie: SingleSpacingGap (0)"
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) metoda

Typ poziomego odstępu między kolumnami macierzy; jednostki odstępu poziomego mogą być w em lub punktach (przechowywane jako twips). Domyślnie: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## Uwagi


Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zobacz także

* Wyliczenie [MathSpacingRules](../../mathspacingrules/)
* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)