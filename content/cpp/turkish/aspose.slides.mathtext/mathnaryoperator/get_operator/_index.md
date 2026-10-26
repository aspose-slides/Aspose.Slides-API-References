---
title: get_Operator()
second_title: Aspose.Slides for C++ API Referansı
description: "Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() metod


Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Açıklamalar


Örnek: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Ayrıca Bakınız

* Sınıf [MathNaryOperator](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)