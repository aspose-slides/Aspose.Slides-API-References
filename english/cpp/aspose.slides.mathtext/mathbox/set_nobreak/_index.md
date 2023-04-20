---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API Reference
description: "No break This property specifies the \"unbreakable\" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true"
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) method


No break This property specifies the \"unbreakable\" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## Remarks


Example: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## See Also

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)