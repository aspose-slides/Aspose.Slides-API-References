---
title: get_ColumnGapRule()
second_title: Aspose.Slides C++ API referencia
description: "A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egysége lehet em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)"
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() metódus


Az egy mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság mértékegysége lehet em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
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