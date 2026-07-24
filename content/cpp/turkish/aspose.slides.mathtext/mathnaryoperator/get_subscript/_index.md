---
title: get_Subscript()
second_title: Aspose.Slides için C++ API Referansı
description: Alt indis argümanını belirtir; örneğin integral durumunda alt sınırı ayarlar
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() yöntemi


Bir alt indis argümanını belirtir; örneğin, bir integral durumunda, alt sınırı ayarlar

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Açıklamalar


Örnek: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathNaryOperator](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)