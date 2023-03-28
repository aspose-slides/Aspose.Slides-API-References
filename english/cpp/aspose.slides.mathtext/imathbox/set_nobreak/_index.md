---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API Reference
description: "No break. This property specifies the \"unbreakable\" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true"
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(**bool**) method


No break. This property specifies the \"unbreakable\" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Remarks


Example: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## See Also

* Class [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
