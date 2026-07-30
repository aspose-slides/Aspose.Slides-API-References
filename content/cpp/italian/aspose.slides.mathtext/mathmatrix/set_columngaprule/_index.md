---
title: set_ColumnGapRule()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere ems o punti (memorizzati come twips). Predefinito: SingleSpacingGap (0)"
type: docs
weight: 118
url: /it/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) metodo

Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere ems o points (memorizzate come twips). Predefinito: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
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