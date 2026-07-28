---
title: set_RowGap()
second_title: "Aspose.Slides dla C++ – Dokumentacja API"
description: "Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule jest ustawiony na 3 (\"Exactly\"), jednostka jest interpretowana jako twipa (1/20 punktu) jeśli RowGapRule jest ustawiony na 4 (\"Multiple\"), jednostka jest interpretowana jako półlinii. Domyślnie: 0"
type: docs
weight: 196
url: /pl/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) metoda

Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule jest ustawiony na 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 punktu) jeśli RowGapRule jest ustawiony na 4 (\"Multiple\"), jednostka jest interpretowana jako półlinii. Domyślnie: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
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