---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API-referencia
description: "A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság mértékegységei lehetnek sorok vagy pontok (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)"
type: docs
weight: 170
url: /hu/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) metódus


A mátrix sorai közötti függőleges távolság típusa; A függőleges távolság egységei lehetnek sorok vagy pontok (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## Megjegyzés


Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Lásd még

* Enum [MathSpacingRules](../../mathspacingrules/)
* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)