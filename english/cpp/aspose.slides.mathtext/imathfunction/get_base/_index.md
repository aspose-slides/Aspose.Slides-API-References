---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: Function Argument
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() method


Function Argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
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
* Class [IMathFunction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
