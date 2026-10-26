---
title: InsertRowBefore()
second_title: Aspose.Slides C++ API Referencia
description: Új sort szúr be a megadott sor előtt. Kezdetben az új sor összes eleme null.
type: docs
weight: 274
url: /hu/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) metódus

Új sort szúr be a megadott sor előtt. Kezdetben az új sor összes eleme null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | **int32_t** | A sor indexe, amely előtt új sort szúrunk be |

## Megjegyzések

Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Lásd még

* Osztály [IMathMatrix](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)