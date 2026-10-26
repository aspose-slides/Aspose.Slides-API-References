---
title: set_ColumnGapRule()
second_title: Aspose.Slides for C++ API Referencia
description: "A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egységei lehetnek em-ek vagy pontok (twip-ben tárolva). Alapértelmezett: SingleSpacingGap (0)"
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) metódus

A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egységei lehetnek em-ek vagy pontok (twip-ben tárolva). Alapértelmezett: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## Megjegyzések

Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Lásd még

* Enum [MathSpacingRules](../../mathspacingrules/)
* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)