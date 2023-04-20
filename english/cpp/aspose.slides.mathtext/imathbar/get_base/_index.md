---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: Base argument
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() method


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## Remarks


Example: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)