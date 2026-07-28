---
title: get_RowGap()
second_title: Aspose.Slides C++ API-referencia
description: "A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra (\"Pontos\"), akkor az egység twipként (a pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re (\"Többszörös\"), akkor az egység fél sorokként értelmeződik. Alapértelmezett: 0"
type: docs
weight: 183
url: /hu/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() metódus


A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra ("Exactly") van állítva, akkor az egység twipként (a pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re ("Multiple") van állítva, akkor az egység fél sorokként értelmeződik. Alapértelmezett: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
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
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)