---
title: get_UpperLimit()
second_title: Aspose.Slides for C++ API Reference
description: Specifies upper or lower limit
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() method


Specifies upper or lower limit

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## Remarks


Example: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## See Also

* Class [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)