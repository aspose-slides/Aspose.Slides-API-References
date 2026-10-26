---
title: set_ColumnGap()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il valore della spaziatura orizzontale tra le colonne di una matrice; se il ColumnGapRule è impostato a 3 (\"Exactly\"), l'unità è interpretata come twip (1/20 di punto) Se il ColumnGapRule è impostato a 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0,5 em. Negli altri casi è ignorato. Predefinito: 0"
type: docs
weight: 144
url: /it/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) metodo

Il valore della spaziatura orizzontale tra le colonne di una matrice; se il ColumnGapRule è impostato a 3 (\"Esattamente\"), l'unità è interpretata come twip (1/20 di punto). Se il ColumnGapRule è impostato a 4 (\"Multiplo\"), l'unità è interpretata come numero di incrementi di 0,5 em. Negli altri casi è ignorato. Predefinito: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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