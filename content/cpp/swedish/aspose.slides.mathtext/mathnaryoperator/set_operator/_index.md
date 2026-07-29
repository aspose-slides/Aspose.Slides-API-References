---
title: set_Operator()
second_title: Aspose.Slides för C++ API-referens
description: "N-är operator-tecken Till exempel: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) metod


N-är operator-tecken Till exempel: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Anmärkningar


Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Se även

* Klass [MathNaryOperator](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)