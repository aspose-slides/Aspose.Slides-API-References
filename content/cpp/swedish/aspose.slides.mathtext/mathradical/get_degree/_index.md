---
title: get_Degree()
second_title: Aspose.Slides för C++ API-referens
description: Degree argument
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() metod


Degree argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Anmärkningar


Exempel: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IMathElement](../../imathelement/)
* klass [MathRadical](../)
* namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)