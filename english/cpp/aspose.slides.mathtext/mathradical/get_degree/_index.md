---
title: get_Degree()
second_title: Aspose.Slides for C++ API Reference
description: Degree argument
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() method


Degree argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Remarks


Example: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathRadical](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
