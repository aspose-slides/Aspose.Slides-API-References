---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API Reference
description: "When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false"
type: docs
weight: 105
url: /aspose.slides.mathtext/mathbox/set_alignmentpoint/
---
## MathBox::set_AlignmentPoint(bool) method


When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

```cpp
void Aspose::Slides::MathText::MathBox::set_AlignmentPoint(bool value) override
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