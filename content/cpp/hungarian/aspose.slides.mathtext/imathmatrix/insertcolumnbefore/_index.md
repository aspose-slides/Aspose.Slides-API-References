---
title: InsertColumnBefore()
second_title: Aspose.Slides C++ API Referenciája
description: Új oszlopot szúr be a megadott előtt. Kezdetben az új oszlop összes eleme null.
type: docs
weight: 313
url: /hu/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) metódus


Új oszlopot szúr be a megadott oszlop elé. Kezdetben az új oszlop összes eleme null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | **int32_t** | Az az oszlop indexe, amely előtt új oszlopot kell beszúrni |
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Lásd még

* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)