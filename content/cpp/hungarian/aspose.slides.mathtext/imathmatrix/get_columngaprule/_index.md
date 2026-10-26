---
title: get_ColumnGapRule()
second_title: Aspose.Slides C++ API referencia
description: "A mátrix oszlopai közötti vízszintes távolság típusa; A vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)"
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() metódus

Egy mátrix oszlopai közötti vízszintes távolság típusa; A vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Megjegyzés

Példa:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Lásd még

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)