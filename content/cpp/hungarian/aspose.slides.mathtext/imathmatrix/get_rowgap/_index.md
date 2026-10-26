---
title: get_RowGap()
second_title: Aspose.Slides C++ API Referenciája
description: "A mátrix sorai közötti függőleges térköz értéke; ha a RowGapRule 3-ra (\"Exactly\") van beállítva, akkor az egység twipként (a pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re (\"Multiple\") van beállítva, akkor az egység fél sorokként értelmeződik. Alapértelmezett: 0"
type: docs
weight: 183
url: /hu/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() metódus

A mátrix sorai közötti függőleges térköz értéke; ha a RowGapRule 3-ra ("Exactly") van beállítva, akkor az egység twipként (a pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re ("Multiple") van beállítva, akkor az egység fél sorokként értelmeződik. Alapértelmezett: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Megjegyzések

Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Lásd még

* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)