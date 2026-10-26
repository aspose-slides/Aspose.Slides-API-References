---
title: set_ColumnGapRule()
second_title: Aspose.Slides C++ API referencia
description: "A mátrix oszlopai közti vízszintes távolság típusa; a vízszintes távolság egységei lehetnek em-ek vagy pontok (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)"
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) metódus

A mátrix oszlopai közti vízszintes távolság típusa; a vízszintes távolság egységei lehetnek em-ek vagy pontok (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## Megjegyzések

Példa:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Lásd még

* Enum [MathSpacingRules](../../mathspacingrules/)
* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)