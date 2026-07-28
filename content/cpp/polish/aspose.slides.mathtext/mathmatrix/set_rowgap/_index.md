---
title: set_RowGap()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule jest ustawiony na 3 (\"Exactly\"), jednostka jest interpretowana jako twipy (1/20 punktu) jeśli RowGapRule jest ustawiony na 4 (\"Multiple\"), jednostka jest interpretowana jako półwiersze. Domyślnie: 0"
type: docs
weight: 196
url: /pl/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) metoda

Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule jest ustawiony na 3 ("Exactly"), jednostka jest interpretowana jako twipy (1/20 punktu) jeśli RowGapRule jest ustawiony na 4 ("Multiple"), jednostka jest interpretowana jako półwiersze. Domyślnie: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
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