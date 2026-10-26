---
title: GetColumnAlignment()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobierz poziome wyrównanie określonej kolumny
type: docs
weight: 248
url: /pl/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) metoda

Pobierz poziome wyrównanie określonej kolumny

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolumny zaczynający się od zera |

### Wartość zwracana

Poziome wyrównanie określonej kolumny
## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Zobacz także

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)