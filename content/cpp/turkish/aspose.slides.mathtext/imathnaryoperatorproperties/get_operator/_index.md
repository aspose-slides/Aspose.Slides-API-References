---
title: get_Operator()
second_title: Aspose.Slides for C++ API Referansı
description: "Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() metodu


Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Açıklamalar


Örnek:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Ayrıca Bakınız

* Sınıf [IMathNaryOperatorProperties](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)