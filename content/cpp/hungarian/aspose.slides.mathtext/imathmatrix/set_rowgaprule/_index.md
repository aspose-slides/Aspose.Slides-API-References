---
title: set_RowGapRule()
second_title: Aspose.Slides C++ API referencia
description: "A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egysége lehet sor vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)"
type: docs
weight: 170
url: /hu/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) metódus

A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egysége lehet sor vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
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