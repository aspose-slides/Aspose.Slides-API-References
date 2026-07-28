---
title: get_RowGapRule()
second_title: Aspose.Slides C++ API referenciája
description: "A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egységei lehetnek sorok vagy pontok (twip-ben tárolva). Alapértelmezett: SingleSpacingGap (0)"
type: docs
weight: 157
url: /hu/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() metódus

A mátrix sorai közötti függőleges távolság típusa; A függőleges távolság egységei lehetnek sorok vagy pontok (twip-ben tárolva). Alapértelmezett: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Megjegyzések

Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Lásd még

* Enum [MathSpacingRules](../../mathspacingrules/)
* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)