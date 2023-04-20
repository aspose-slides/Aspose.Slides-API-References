---
title: set_RowGap()
second_title: Aspose.Slides for C++ API Reference
description: "The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 (\"Exactly\"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 (\"Multiple\"), then the unit is interpreted as half-lines. Default: 0"
type: docs
weight: 196
url: /cpp/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) method


The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 (\"Exactly\"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 (\"Multiple\"), then the unit is interpreted as half-lines. Default: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## Remarks


Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## See Also

* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)