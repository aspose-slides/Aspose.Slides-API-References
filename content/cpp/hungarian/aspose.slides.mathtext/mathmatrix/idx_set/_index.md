---
title: idx_set()
second_title: Aspose.Slides C++ API referenciája
description: Mátrix eleme
type: docs
weight: 222
url: /hu/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) metódus


A mátrix eleme

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| row | **int32_t** | A sor indexe nulla-alapú a lekérdezni kívánt elemhez |
| column | **int32_t** | Az oszlop indexe nulla-alapú a lekérdezni kívánt elemhez |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)