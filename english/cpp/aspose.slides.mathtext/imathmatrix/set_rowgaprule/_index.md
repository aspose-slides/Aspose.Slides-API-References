---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API Reference
description: "The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0)"
type: docs
weight: 170
url: /cpp/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) method


The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## Remarks


Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## See Also

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)