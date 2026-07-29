---
title: get_Operator()
second_title: Aspose.Slides för C++ API-referens
description: "Nary-operatortecken Till exempel: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() metod


Nary Operator-tecken Till exempel: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Anmärkningar


Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Se även

* Klass [IMathNaryOperatorProperties](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)