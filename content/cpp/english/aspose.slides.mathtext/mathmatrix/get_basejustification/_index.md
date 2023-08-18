---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center"
type: docs
weight: 53
url: /aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() method


Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## Remarks


Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## See Also

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)