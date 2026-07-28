---
title: set_ColumnGap()
second_title: Aspose.Slides C++ API Referencia
description: "A mátrix oszlopai közötti vízszintes hézag értéke; ha a ColumnGapRule értéke 3 (\"Exactly\"), akkor az egység twipben (a pont húszad része) értelmeződik. Ha a ColumnGapRule értéke 4 (\"Multiple\"), akkor az egység 0,5 em lépések számaként értelmeződik. Más esetekben figyelmen kívül marad. Alapértelmezett: 0"
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) metódus

A mátrix oszlopai közötti vízszintes hézag értéke; ha a ColumnGapRule értéke 3 (\"Exactly\"), akkor az egység twipben (a pont húszad része) értelmeződik. Ha a ColumnGapRule értéke 4 (\"Multiple\"), akkor az egység 0,5 em lépésként értelmeződik. Más esetekben figyelmen kívül marad. Alapértelmezett: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## Megjegyzések

Példa:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Lásd még

* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)