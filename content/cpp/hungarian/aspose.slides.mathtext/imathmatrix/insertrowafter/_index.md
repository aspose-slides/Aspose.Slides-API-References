---
title: InsertRowAfter()
second_title: Aspose.Slides C++ API referenciája
description: Új sort szúr be a megadott sor után. Kezdetben az új sor minden eleme null.
type: docs
weight: 287
url: /hu/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) metódus


Új sort szúr be a megadott sor után. Kezdetben az új sor minden eleme null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | **int32_t** | Annak a sornak az indexe, amely után új sort szúrunk be |
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Lásd még

* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)