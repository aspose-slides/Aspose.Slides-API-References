---
title: set_ColumnGap()
second_title: Aspose.Slides dla C++ - referencja API
description: "Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule jest ustawione na 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 punktu) jeśli ColumnGapRule jest ustawione na 4 (\"Multiple\"), jednostka jest interpretowana jako liczba przyrostów 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0"
type: docs
weight: 144
url: /pl/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) metoda


Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule jest ustawione na 3 ("Exactly"), jednostka jest interpretowana jako twips (1/20th of a point) jeśli ColumnGapRule jest ustawione na 4 ("Multiple"), jednostka jest interpretowana jako liczba przyrostów 0.5 em. W innych przypadkach ignorowane. Domyślnie: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## Uwagi


Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Zobacz także

* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)