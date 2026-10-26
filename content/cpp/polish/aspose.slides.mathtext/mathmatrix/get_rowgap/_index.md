---
title: get_RowGap()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Wartość pionowego odstępu między wierszami macierzy; Jeśli RowGapRule jest ustawiony na 3 (\"Exactly\"), jednostka jest interpretowana jako twipy (1/20 punktu) Jeśli RowGapRule jest ustawiony na 4 (\"Multiple\"), jednostka jest interpretowana jako pół-linii. Domyślnie: 0"
type: docs
weight: 183
url: /pl/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() metoda

Wartość pionowego odstępu między wierszami macierzy; Jeśli RowGapRule jest ustawiony na 3 ("Exactly"), jednostka jest interpretowana jako twipy (1/20 punktu) Jeśli RowGapRule jest ustawiony na 4 ("Multiple"), jednostka jest interpretowana jako pół-linii. Domyślnie: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Uwagi

Przykład:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Zobacz także

* Klasa [MathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)