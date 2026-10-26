---
title: get_ColumnGap()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il valore della spaziatura orizzontale tra le colonne di una matrice; se la ColumnGapRule è impostata a 3 (\"Exactly\"), l'unità è interpretata come twips (1/20 di punto) se la ColumnGapRule è impostata a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0.5 em. In altri casi viene ignorato. Predefinito: 0"
type: docs
weight: 131
url: /it/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() method

Il valore della spaziatura orizzontale tra le colonne di una matrice; se la ColumnGapRule è impostata a 3 (\"Exactly\"), l'unità è interpretata come twips (1/20 di punto) se la ColumnGapRule è impostata a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0,5 em. In altri casi viene ignorato. Predefinito: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Osservazioni

Esempio: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Vedi anche

* Classe [MathMatrix](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)