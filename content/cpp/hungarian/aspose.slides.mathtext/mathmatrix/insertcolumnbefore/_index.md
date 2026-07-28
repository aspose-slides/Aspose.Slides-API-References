---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API-referencia
description: Új oszlop beszúrása a megadott előtt. Alapértelmezés szerint az új oszlop összes eleme null.
type: docs
weight: 326
url: /hu/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) method


Új oszlop beszúrása a megadott előtt. Alapértelmezés szerint az új oszlop minden eleme null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | **int32_t** | Az a oszlop indexe, amely előtt egy új oszlopot szúrunk be |
## Megjegyzés



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Lásd még

* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)