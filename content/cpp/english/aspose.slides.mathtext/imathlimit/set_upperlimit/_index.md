---
title: set_UpperLimit()
second_title: Aspose.Slides for C++ API Reference
description: Specifies upper or lower limit
type: docs
weight: 40
url: /aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) method


Specifies upper or lower limit

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
```

## Remarks


Example: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## See Also

* Class [IMathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)