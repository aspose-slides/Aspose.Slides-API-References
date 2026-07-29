---
title: set_Operator()
second_title: Aspose.Slides för C++ API-referens
description: "Nary-operatortecken Till exempel: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) metod


Nary Operator-tecken Till exempel: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
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