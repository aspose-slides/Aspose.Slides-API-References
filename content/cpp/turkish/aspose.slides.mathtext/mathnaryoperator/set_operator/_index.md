---
title: set_Operator()
second_title: Aspose.Slides for C++ API Referansı
description: "Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) yöntemi


Nary Operatör Karakteri Örneğin: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Açıklamalar


Örnek:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Ayrıca Bakınız

* Sınıf [MathNaryOperator](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)