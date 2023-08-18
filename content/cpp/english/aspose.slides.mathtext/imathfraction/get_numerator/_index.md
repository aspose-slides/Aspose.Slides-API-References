---
title: get_Numerator()
second_title: Aspose.Slides for C++ API Reference
description: Numerator
type: docs
weight: 27
url: /aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMathFraction::get_Numerator() method


Numerator

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
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
* Class [IMathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)