---
title: set_RowGap()
second_title: Aspose.Slides for C++ API referenciája
description: "A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra (\"Exactly\") van beállítva, akkor az egység twipként (a pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re (\"Multiple\") van beállítva, akkor az egység fél-sorokként értelmeződik. Alapértelmezett: 0"
type: docs
weight: 196
url: /hu/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) metódus


A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-re (\"Exactly\") van beállítva, akkor az egység twipként (a pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re (\"Multiple\") van beállítva, akkor az egység fél-sorokként értelmeződik. Alapértelmezett: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
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