---
title: set_ColumnGapRule()
second_title: Aspose.Slides for C++ API Reference
description: "The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0)"
type: docs
weight: 118
url: /aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) method


The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## Remarks


Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## See Also

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)