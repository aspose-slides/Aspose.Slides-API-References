---
title: GetColumnAlignment()
second_title: Referencja API Aspose.Slides dla C++
description: Pobiera poziome wyrównanie określonej kolumny
type: docs
weight: 235
url: /pl/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) metoda

Pobiera poziome wyrównanie określonej kolumny

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolumny liczony od zera |

### Wartość zwracana

Poziome wyrównanie określonej kolumny
## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Zobacz także

* Wyliczenie [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)