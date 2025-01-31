---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center"
type: docs
weight: 66
url: /aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) method


Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
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