---
title: get_ColumnGapRule()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). Default: SingleSpacingGap (0)"
type: docs
weight: 105
url: /it/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() metodo


Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). Default: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Osservazioni


Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Vedi anche

* Enum [MathSpacingRules](../../mathspacingrules/)
* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)