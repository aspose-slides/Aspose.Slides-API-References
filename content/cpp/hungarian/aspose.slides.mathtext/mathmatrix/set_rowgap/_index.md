---
title: set_RowGap()
second_title: Aspose.Slides C++ API referencia
description: "A mátrix sorai közötti függőleges térköz értéke; ha a RowGapRule 3-ra (\"Exactly\") van beállítva, akkor a mértékegység twipként (a pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re (\"Multiple\") van beállítva, akkor a mértékegység fél sorokként értelmeződik. Alapértelmezett: 0"
type: docs
weight: 196
url: /hu/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) metódus


A mátrix sorai közötti függőleges térköz értéke; ha a RowGapRule 3-ra (\"Exactly\") van beállítva, akkor a mértékegység twipként (a pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re (\"Multiple\") van beállítva, akkor a mértékegység fél sorokként értelmeződik. Alapértelmezett: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## Megjegyzések


Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Lásd még

* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)