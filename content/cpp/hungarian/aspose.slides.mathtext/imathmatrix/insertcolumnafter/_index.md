---
title: InsertColumnAfter()
second_title: Aspose.Slides for C++ API-referencia
description: Új oszlopot szúr be a megadott után. Az új oszlop összes eleme kezdetben null értékű.
type: docs
weight: 326
url: /hu/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) metódus

Új oszlopot szúr be a megadott után. Az új oszlop összes eleme kezdetben null értékű.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | **int32_t** | Az a oszlopindex, amely után egy újat szúr be |
## Megjegyzés



Példa:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Lásd még

* Osztály [IMathMatrix](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)