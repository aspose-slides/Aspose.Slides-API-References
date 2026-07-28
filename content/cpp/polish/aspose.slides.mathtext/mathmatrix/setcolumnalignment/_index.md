---
title: SetColumnAlignment()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Ustawia wyrównanie poziome określonej kolumny
type: docs
weight: 261
url: /pl/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metoda


Ustawia wyrównanie poziome określonej kolumny

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
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
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)