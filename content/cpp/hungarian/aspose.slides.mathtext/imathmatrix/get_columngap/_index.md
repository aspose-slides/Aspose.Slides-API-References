---
title: get_ColumnGap()
second_title: Aspose.Slides C++ API referencia
description: "A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule értéke 3 (\"Exactly\"), akkor az egység twip-ben (a pont 1/20-a) értelmeződik. Ha a ColumnGapRule értéke 4 (\"Multiple\"), akkor az egység 0,5 em lépés számaként értelmeződik. Egyéb esetekben figyelmen kívül hagyott. Alapértelmezett: 0"
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() metódus


A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule értéke 3 ("Exactly"), akkor az egység twip-ben (a pont 1/20-a) értelmeződik. Ha a ColumnGapRule értéke 4 ("Multiple"), akkor az egység 0,5 em lépés számaként értelmeződik. Egyéb esetekben figyelmen kívül hagyott. Alapértelmezett: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
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