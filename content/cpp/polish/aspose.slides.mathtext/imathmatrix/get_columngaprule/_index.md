---
title: get_ColumnGapRule()
second_title: Aspose.Slides dla C++ Referencja API
description: "Typ poziomego odstępu pomiędzy kolumnami macierzy; jednostki poziomego odstępu mogą być w ems lub punktach (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)"
type: docs
weight: 105
url: /pl/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() metoda


Typ poziomego odstępu pomiędzy kolumnami macierzy; jednostki odstępu poziomego mogą być w ems lub punktach (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Uwagi


Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zobacz również

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)