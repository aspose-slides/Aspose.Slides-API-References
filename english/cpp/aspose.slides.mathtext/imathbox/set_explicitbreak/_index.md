---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API Reference
description: "Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)"
type: docs
weight: 131
url: /cpp/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) method


Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
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