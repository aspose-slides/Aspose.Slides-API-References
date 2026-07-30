---
title: get_ColumnGapRule()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)"
type: docs
weight: 105
url: /it/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() metodo

Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## Osservazioni

Esempio:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Vedi anche

* Enum [MathSpacingRules](../../mathspacingrules/)
* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)