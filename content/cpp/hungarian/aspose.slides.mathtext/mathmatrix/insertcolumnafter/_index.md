---
title: InsertColumnAfter()
second_title: Aspose.Slides C++ API hivatkozás
description: Új oszlopot szúr be a megadott oszlop után. Kezdetben az új oszlop összes eleme null értékű.
type: docs
weight: 339
url: /hu/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) metódus


Új oszlopot szúr be a megadott oszlop után. Kezdetben az új oszlop összes eleme null értékű.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | **int32_t** | Az oszlop indexe, amely után egy újat kell beszúrni |
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Lásd még

* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)