---
title: get_ColumnGap()
second_title: Aspose.Slides dla C++ – referencja API
description: "Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule jest ustawiony na 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 części punktu) jeśli ColumnGapRule jest ustawiony na 4 (\"Multiple\"), jednostka jest interpretowana jako liczba przyrostów 0.5 em. W innych przypadkach ignorowane. Domyślnie: 0"
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() metoda


Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule jest ustawiony na 3 ("Exactly"), jednostka jest interpretowana jako twips (1/20th of a point) jeśli ColumnGapRule jest ustawiony na 4 ("Multiple"), jednostka jest interpretowana jako liczba przyrostów 0.5 em. W innych przypadkach ignorowane. Domyślnie: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Uwagi


Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Zobacz także

* Klasa [MathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)