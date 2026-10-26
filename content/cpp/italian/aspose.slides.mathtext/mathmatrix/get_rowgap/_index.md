---
title: get_RowGap()
second_title: Aspose.Slides per C++ Riferimento API
description: "Il valore della spaziatura verticale tra le righe di una matrice; se il RowGapRule è impostato su 3 (\"Exactly\"), allora l'unità è interpretata come twips (1/20 di un punto) se il RowGapRule è impostato su 4 (\"Multiple\"), allora l'unità è interpretata come mezze linee. Predefinito: 0"
type: docs
weight: 183
url: /it/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() metodo

Il valore della spaziatura verticale tra le righe di una matrice; Se il RowGapRule è impostato su 3 (\"Exactly\"), l'unità è interpretata come twips (1/20 di un punto) Se il RowGapRule è impostato su 4 (\"Multiple\"), l'unità è interpretata come mezze linee. Predefinito: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Osservazioni


Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Vedi anche

* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)