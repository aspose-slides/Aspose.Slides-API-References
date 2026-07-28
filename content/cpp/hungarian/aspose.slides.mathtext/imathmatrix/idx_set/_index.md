---
title: idx_set()
second_title: Aspose.Slides for C++ API referencia
description: A mátrix elemei
type: docs
weight: 222
url: /hu/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) metódus


Mátrix elemei

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| row | **int32_t** | A sor nulla-alapú indexe az elem lekéréséhez |
| column | **int32_t** | Az oszlop nulla-alapú indexe az elem lekéréséhez |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
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