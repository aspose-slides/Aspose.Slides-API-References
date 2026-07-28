---
title: get_MinColumnWidth()
second_title: Aspose.Slides C++ API referencia
description: "A minimum oszlopszélesség twipben (a pont 1/20-a) A hézag távolság (más néven \\u201CColumn Gap\\u201D vagy \\u201CGap Width\\u201D) hozzáadódik a MinColumnWidth-hez, hogy meghatározza a teljes Matrix Column Spacing-et (a különböző oszlopok azonos élei közötti távolság). Alapértelmezett: 0."
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() metódus


A minimum oszlopszélesség twipben (1/20.-a egy pontnak). A hézag távolság (más néven \\u201CColumn Gap\\u201D vagy \\u201CGap Width\\u201D) hozzáadódik a MinColumnWidth-hez, hogy meghatározza a teljes Matrix [Column](../../../aspose.slides/column/) Spacing-et (a különböző oszlopok azonos élei közötti távolság). Alapértelmezett: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## Megjegyzések


Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Lásd még

* Osztály [IMathMatrix](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)