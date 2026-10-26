---
title: idx_get()
second_title: Odniesienie do API Aspose.Slides dla C++
description: Element macierzy
type: docs
weight: 209
url: /pl/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) metoda


Element macierzy

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| row | **int32_t** | Indeks zerowy wiersza, z którego pobierany jest element |
| column | **int32_t** | Indeks zerowy kolumny, z której pobierany jest element |

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
* Klasa [MathMatrix](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)