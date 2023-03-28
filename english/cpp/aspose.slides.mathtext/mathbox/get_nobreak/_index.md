---
title: get_NoBreak()
second_title: Aspose.Slides for C++ API Reference
description: "No break This property specifies the \"unbreakable\" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true"
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() method


No break This property specifies the \"unbreakable\" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
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
