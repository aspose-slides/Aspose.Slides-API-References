---
title: idx_get()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Prvek matice
type: docs
weight: 209
url: /cs/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) metoda

Element of matrix

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| row | **int32_t** | Nulový index řádku pro získání položky |
| column | **int32_t** | Nulový index sloupce pro získání položky |

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
* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)