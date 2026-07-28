---
title: SetColumnsAlignment()
second_title: Aspose.Slides dla C++ Odniesienie API
description: Ustaw poziome wyrównanie określonych kolumn
type: docs
weight: 274
url: /pl/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metoda


Ustaw poziome wyrównanie określonych kolumn

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks zerowy pierwszej kolumny, której wyrównanie ma zostać ustawione |
| columnsCount | **uint32_t** | Liczba kolumn, dla których należy określić wyrównanie |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nowa wartość poziomego wyrównania określonej kolumny |
## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Zobacz także

* Wyliczenie [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasa [MathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)