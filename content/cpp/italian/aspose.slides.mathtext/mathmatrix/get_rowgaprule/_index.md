---
title: get_RowGapRule()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)"
type: docs
weight: 157
url: /it/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() method

Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## Osservazioni

Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Vedi anche

* Enum [MathSpacingRules](../../mathspacingrules/)
* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)