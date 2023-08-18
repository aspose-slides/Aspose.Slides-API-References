---
title: get_Name()
second_title: Aspose.Slides for C++ API Reference
description: Function name For example, function names are sin and cos
type: docs
weight: 1
url: /aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() method


Function name For example, function names are sin and cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Remarks


Example: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathFunction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)