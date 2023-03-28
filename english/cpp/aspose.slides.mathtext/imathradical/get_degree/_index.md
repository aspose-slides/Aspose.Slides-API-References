---
title: get_Degree()
second_title: Aspose.Slides for C++ API Reference
description: Degree argument
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() method


Degree argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Remarks


Example: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // cube root
auto degreeElem = radical->get_Degree();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathRadical](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
