---
title: get_AlignmentPoint()
second_title: Aspose.Slides for C++ API Reference
description: "When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false"
type: docs
weight: 92
url: /cpp/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() method


When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## Remarks


Example: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## See Also

* Class [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)