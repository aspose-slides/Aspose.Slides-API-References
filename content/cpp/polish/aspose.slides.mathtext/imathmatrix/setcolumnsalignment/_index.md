---
title: SetColumnsAlignment()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia poziome wyrównanie określonych kolumn
type: docs
weight: 261
url: /pl/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metoda

Ustawia poziome wyrównanie określonych kolumn

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks zerowy pierwszej kolumny, dla której ma zostać ustawione wyrównanie |
| columnsCount | **uint32_t** | Liczba kolumn, dla których ma zostać określone wyrównanie |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nowa wartość poziomego wyrównania określonej kolumny |
## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Zobacz także

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)