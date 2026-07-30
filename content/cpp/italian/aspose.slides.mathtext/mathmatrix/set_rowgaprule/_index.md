---
title: set_RowGapRule()
second_title: Riferimento API Aspose.Slides per C++
description: "Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twips). Predefinito: SingleSpacingGap (0)"
type: docs
weight: 170
url: /it/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) metodo


Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twips). Predefinito: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
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
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)