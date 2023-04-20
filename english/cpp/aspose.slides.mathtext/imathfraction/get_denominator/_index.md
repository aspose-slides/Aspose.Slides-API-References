---
title: get_Denominator()
second_title: Aspose.Slides for C++ API Reference
description: Denominator
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() method


Denominator

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## Remarks


Example: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)