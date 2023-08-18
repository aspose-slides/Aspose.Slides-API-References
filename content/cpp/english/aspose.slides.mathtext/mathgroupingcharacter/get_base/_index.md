---
title: get_Base()
second_title: Aspose.Slides for C++ API Reference
description: Base argument
type: docs
weight: 1
url: /aspose.slides.mathtext/mathgroupingcharacter/get_base/
---
## MathGroupingCharacter::get_Base() method


Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathGroupingCharacter::get_Base() override
```

## Remarks


Example: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)