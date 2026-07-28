---
title: idx_get()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Elementy macierzy
type: docs
weight: 209
url: /pl/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) metoda

Elementy macierzy

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| row | **int32_t** | Indeks bazujący na zerze wiersza, z którego pobierany jest element |
| column | **int32_t** | Indeks bazujący na zerze kolumny, z której pobierany jest element |

### Wartość zwracana


## Uwagi



Przykład: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)