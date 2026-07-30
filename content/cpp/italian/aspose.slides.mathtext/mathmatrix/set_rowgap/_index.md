---
title: set_RowGap()
second_title: Riferimento API Aspose.Slides per C++
description: "Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twips (1/20 di punto) se RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezza riga. Predefinito: 0"
type: docs
weight: 196
url: /it/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) metodo

Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 ("Exactly"), l'unità è interpretata come twips (1/20 di punto) se RowGapRule è impostato a 4 ("Multiple"), l'unità è interpretata come mezze righe. Predefinito: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
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
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)