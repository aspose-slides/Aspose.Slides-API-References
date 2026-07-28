---
title: idx_get()
second_title: Aspose.Slides C++ API hivatkozás
description: Mátrix eleme
type: docs
weight: 209
url: /hu/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) metódus


Mátrix eleme

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| row | **int32_t** | A sor nulla-alapú indexe az elem lekéréséhez |
| column | **int32_t** | A oszlop nulla-alapú indexe az elem lekéréséhez |

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
* Osztály [MathMatrix](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)