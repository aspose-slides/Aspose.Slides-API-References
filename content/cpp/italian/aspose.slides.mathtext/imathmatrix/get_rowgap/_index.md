---
title: get_RowGap()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il valore della spaziatura verticale tra le righe di una matrice; se il RowGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se il RowGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come mezza linea. Predefinito: 0"
type: docs
weight: 183
url: /it/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() metodo

Il valore della spaziatura verticale tra le righe di una matrice; Se il RowGapRule è impostato a 3 ("Exactly"), l'unità viene interpretata come twip (1/20 di punto) Se il RowGapRule è impostato a 4 ("Multiple"), l'unità viene interpretata come mezza linea. Predefinito: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
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
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)