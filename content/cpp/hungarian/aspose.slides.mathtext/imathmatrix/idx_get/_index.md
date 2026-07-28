---
title: idx_get()
second_title: Aspose.Slides C++ API Referenciája
description: A mátrix elemei
type: docs
weight: 209
url: /hu/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) metódus


Mátrix elemei

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| row | **int32_t** | A sor nulláral indított indexe az elem lekéréséhez |
| column | **int32_t** | Az oszlop nulláral indított indexe az elem lekéréséhez |

### Visszatérési érték


## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)