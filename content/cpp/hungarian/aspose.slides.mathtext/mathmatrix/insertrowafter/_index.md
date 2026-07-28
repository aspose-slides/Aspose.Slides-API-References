---
title: InsertRowAfter()
second_title: Aspose.Slides C++ API referenciája
description: Új sort szúr be a megadott sor után. Kezdetben az új sor összes eleme null értékű.
type: docs
weight: 300
url: /hu/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) metódus


Szúrjon be egy új sort a megadott sor után. Kezdetben az új sor összes eleme null értékű.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | **int32_t** | A sor indexe, amely után egy új sort kell beszúrni |
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Lásd még

* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)