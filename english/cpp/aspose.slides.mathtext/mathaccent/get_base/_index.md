---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: The argument to which the accent was applied
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() method


The argument to which the accent was applied

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Remarks


Example: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
