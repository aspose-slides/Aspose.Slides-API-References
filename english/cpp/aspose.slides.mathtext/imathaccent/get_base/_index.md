---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: The argument to which the accent was applied
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() method


The argument to which the accent was applied

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
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
* Class [IMathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
