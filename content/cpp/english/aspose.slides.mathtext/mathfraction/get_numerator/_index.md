---
title: get_Numerator()
second_title: Aspose.Slides for C++ API Reference
description: Numerator
type: docs
weight: 27
url: /aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() method


Numerator

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
```

## Remarks


Example: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)