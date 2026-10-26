---
title: set_ColumnGap()
second_title: Aspose.Slides C++ API hivatkozás
description: "A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra (\"Exactly\") van beállítva, akkor az egység twipként (a pont 1/20-a) értelmeződik. Ha a ColumnGapRule 4-re (\"Multiple\") van beállítva, akkor az egység 0,5 em lépések számaként értelmeződik. Más esetekben figyelmen kívül marad. Alapértelmezett: 0"
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) metódus


A mátrix oszlopai közötti vízszintes távolság értéke; Ha a ColumnGapRule 3-ra (\"Exactly\") van beállítva, akkor az egység twipként (a pont 1/20-a) értelmeződik. Ha a ColumnGapRule 4-re (\"Multiple\") van beállítva, akkor az egység 0,5 em növekmények számaként értelmeződik. Más esetekben figyelmen kívül marad. Alapértelmezett: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
```

## Megjegyzések


Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Lásd még

* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)