---
title: set_UpperLimit()
second_title: Aspose.Slides for C++ API Reference
description: Specifies upper or lower limit
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(**bool**) method


Specifies upper or lower limit

```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
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
