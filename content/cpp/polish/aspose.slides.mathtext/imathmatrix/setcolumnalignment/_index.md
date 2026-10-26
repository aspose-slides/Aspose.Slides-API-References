---
title: SetColumnAlignment()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia wyrównanie poziome określonej kolumny
type: docs
weight: 248
url: /pl/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metoda

Ustaw wyrównanie poziome określonej kolumny

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolumny zaczynający się od zera |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nowa wartość wyrównania poziomego określonej kolumny |
## Uwagi

Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Zobacz także

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)