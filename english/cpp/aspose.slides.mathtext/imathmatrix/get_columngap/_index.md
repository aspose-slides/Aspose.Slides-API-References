---
title: get_ColumnGap()
second_title: Aspose.Slides for C++ API Reference
description: "The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 (\"Exactly\"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 (\"Multiple\"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0"
type: docs
weight: 131
url: /cpp/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() method


The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 (\"Exactly\"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 (\"Multiple\"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Remarks


Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## See Also

* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
