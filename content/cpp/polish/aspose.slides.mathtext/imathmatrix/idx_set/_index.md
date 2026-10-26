---
title: idx_set()
second_title: Aspose.Slides dla C++ - Referencja API
description: Elementy macierzy
type: docs
weight: 222
url: /pl/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) metoda


Elementy macierzy

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| row | **int32_t** | Zero-based indeks wiersza row, z którego pobierany jest element |
| column | **int32_t** | Zero-based indeks kolumny column, z którego pobierany jest element |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
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