---
title: get_Subscript()
second_title: Aspose.Slides için C++ API Referansı
description: Örneğin bir integral durumunda alt sınırı belirleyen bir alt indis argümanını tanımlar
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() metod


Bir integral durumunda, alt sınırı belirleyen bir alt indis argümanını belirtir

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## Açıklamalar


Örnek: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)