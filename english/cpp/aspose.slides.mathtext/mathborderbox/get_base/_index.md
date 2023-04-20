---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: Base argument
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/mathborderbox/get_base/
---
## MathBorderBox::get_Base() method


Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBorderBox::get_Base() override
```

## Remarks


Example: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = borderBox->get_Base();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)