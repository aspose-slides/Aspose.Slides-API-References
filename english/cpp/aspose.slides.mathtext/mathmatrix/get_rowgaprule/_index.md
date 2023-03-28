---
title: get_RowGapRule()
second_title: Aspose.Slides for C++ API Reference
description: "The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0)"
type: docs
weight: 157
url: /cpp/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() method


The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## Remarks


Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## See Also

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
