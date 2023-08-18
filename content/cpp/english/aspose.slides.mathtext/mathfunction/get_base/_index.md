---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: Function Argument
type: docs
weight: 14
url: /aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() method


Function Argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Remarks


Example: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathFunction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)