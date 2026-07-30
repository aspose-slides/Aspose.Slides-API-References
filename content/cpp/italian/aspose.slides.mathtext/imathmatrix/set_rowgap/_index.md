---
title: set_RowGap()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato su 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se RowGapRule è impostato su 4 (\"Multiple\"), l'unità è interpretata come mezza linea. Predefinito: 0"
type: docs
weight: 196
url: /it/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) metodo

Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato su 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto). Se RowGapRule è impostato su 4 (\"Multiple\"), l'unità è interpretata come mezze righe. Predefinito: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
```

## Osservazioni

Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Vedi anche

* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)