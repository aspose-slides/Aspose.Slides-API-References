---
title: idx_get()
second_title: Aspose.Slides pro C++ API Reference
description: Prvky matice
type: docs
weight: 209
url: /cs/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) method

Prvky matice

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| row | **int32_t** | Nulový index řádku, pro který se získá prvek |
| column | **int32_t** | Nulový index sloupce, pro který se získá prvek |

### Návratová hodnota


## Poznámky



Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)