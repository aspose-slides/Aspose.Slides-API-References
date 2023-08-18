---
title: get_ExplicitBreak()
second_title: Aspose.Slides for C++ API Reference
description: "Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)"
type: docs
weight: 118
url: /aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() method


Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Remarks


Example: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## See Also

* Class [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)