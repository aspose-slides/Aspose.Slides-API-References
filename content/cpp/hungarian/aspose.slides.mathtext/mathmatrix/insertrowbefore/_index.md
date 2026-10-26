---
title: InsertRowBefore()
second_title: Aspose.Slides C++ API Referencia
description: Új sort szúr be a megadott sor elé. Az új sor összes eleme kezdetben null értékű.
type: docs
weight: 287
url: /hu/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) metódus


Új sort szúr be a megadott sor elé. A új sor minden eleme kezdetben null értékű.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | **int32_t** | Annak a sornak az indexe, amely előtt egy újat szúrunk be |
## Megjegyzések



Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Lásd még

* Osztály [MathMatrix](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)