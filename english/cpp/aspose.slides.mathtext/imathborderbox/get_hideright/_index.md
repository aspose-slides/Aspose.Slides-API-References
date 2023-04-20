---
title: get_HideRight()
second_title: Aspose.Slides for C++ API Reference
description: Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box.
type: docs
weight: 92
url: /cpp/aspose.slides.mathtext/imathborderbox/get_hideright/
---
## IMathBorderBox::get_HideRight() method


Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideRight()=0
```

## Remarks


Example: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideRight(true);
```

## See Also

* Class [IMathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)