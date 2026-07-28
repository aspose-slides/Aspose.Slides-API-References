---
title: get_ColumnGap()
second_title: Aspose.Slides C++ API hivatkozás
description: "Az mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule értéke 3 (\"Exactly\"), akkor az egységet twipként (egy pont 1/20-a) értelmezi. Ha a ColumnGapRule értéke 4 (\"Multiple\"), akkor az egységet 0,5 em lépések számaként értelmezi. Egyéb esetekben figyelmen kívül marad. Alapértelmezett: 0"
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() metódus

A mátrix oszlopai közötti vízszintes távolság értéke; Ha a ColumnGapRule értéke 3 („Exactly”), akkor az egységet twipként (pont 1/20-a) értelmezi. Ha a ColumnGapRule értéke 4 („Multiple”), akkor az egységet 0,5 em lépésszámként értelmezi. Egyéb esetben figyelmen kívül van hagyva. Alapértelmezett: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
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