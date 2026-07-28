---
title: set_ColumnGap()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma ustawioną wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 punktu) Jeśli ColumnGapRule ma ustawioną wartość 4 (\"Multiple\"), jednostka jest interpretowana jako liczba przyrostów 0.5 em. W innych przypadkach ignorowana. Domyślnie: 0"
type: docs
weight: 144
url: /pl/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) metoda

Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma ustawioną wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma ustawioną wartość 4 (\"Multiple\"), jednostka jest interpretowana jako liczba przyrostów 0.5 em. W innych przypadkach jest ignorowana. Domyślnie: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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