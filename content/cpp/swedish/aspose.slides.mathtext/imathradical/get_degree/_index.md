---
title: get_Degree()
second_title: Aspose.Slides för C++ API-referens
description: Gradargument
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() metod

Degree argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Anmärkningar


Exempel: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // kubrot
auto degreeElem = radical->get_Degree();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathRadical](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)