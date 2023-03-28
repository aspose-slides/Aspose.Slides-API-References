---
title: get_Limit()
second_title: Aspose.Slides for C++ API Reference
description: Limit argument
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() method


Limit argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Remarks


Example: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
