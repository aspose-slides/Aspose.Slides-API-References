---
title: get_ColumnGap()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) se ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0,5 em. In altri casi ignorato. Predefinito: 0"
type: docs
weight: 131
url: /it/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() metodo

Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 ("Exactly"), l'unità è interpretata come twip (1/20 di punto) se ColumnGapRule è impostato a 4 ("Multiple"), l'unità è interpretata come numero di incrementi di 0,5 em. In altri casi ignorato. Predefinito: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Osservazioni

Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Vedi anche

* Classe [IMathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)