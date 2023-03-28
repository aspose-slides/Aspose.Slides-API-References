---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center"
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() method


Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Remarks


Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## See Also

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
