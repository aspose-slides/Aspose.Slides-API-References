---
title: get_RowGapRule()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)"
type: docs
weight: 157
url: /it/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() metodo

Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Osservazioni

Esempio:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Vedi anche

* Enumerazione [MathSpacingRules](../../mathspacingrules/)
* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)