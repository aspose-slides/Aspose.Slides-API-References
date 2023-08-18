---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API Reference
description: "The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0)"
type: docs
weight: 105
url: /aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() method


The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Remarks


Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## See Also

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)