---
title: set_RowGap()
second_title: Aspose.Slides for C++ API Reference
description: "The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 (\"Exactly\"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 (\"Multiple\"), then the unit is interpreted as half-lines. Default: 0"
type: docs
weight: 196
url: /aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) method


The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 (\"Exactly\"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 (\"Multiple\"), then the unit is interpreted as half-lines. Default: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
```

## Remarks


Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## See Also

* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)