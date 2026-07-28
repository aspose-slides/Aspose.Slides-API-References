---
title: get_RowGapRule()
second_title: Aspose.Slides C++ API referencia
description: "A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egysége lehet sor vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)"
type: docs
weight: 157
url: /hu/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() metódus

A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság mértékegysége lehet sor vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## Megjegyzések

Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Lásd még

* Enum [MathSpacingRules](../../mathspacingrules/)
* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)