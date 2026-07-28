---
title: get_ColumnGap()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule jest ustawiony na 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule jest ustawiony na 4 (\"Multiple\"), jednostka jest interpretowana jako liczba przyrostów 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0"
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() metoda


Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule jest ustawiony na 3 ("Exactly"), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule jest ustawiony na 4 ("Multiple"), jednostka jest interpretowana jako liczba przyrostów 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
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