---
title: get_AlignmentPoint()
second_title: Aspose.Slides for C++ API Reference
description: "When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false"
type: docs
weight: 92
url: /cpp/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() method


When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## Remarks


Example: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## See Also

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)