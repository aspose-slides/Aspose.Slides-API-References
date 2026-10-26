---
title: get_RowGap()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule jest ustawione na 3 (\"Exactly\"), jednostka jest interpretowana jako twipy (1/20 punktu) jeśli RowGapRule jest ustawione na 4 (\"Multiple\"), jednostka jest interpretowana jako półwiersze. Domyślnie: 0"
type: docs
weight: 183
url: /pl/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() metoda


Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule jest ustawione na 3 ("Exactly"), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli RowGapRule jest ustawione na 4 ("Multiple"), jednostka jest interpretowana jako półwiersze. Domyślnie: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Uwagi


Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Zobacz także

* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)