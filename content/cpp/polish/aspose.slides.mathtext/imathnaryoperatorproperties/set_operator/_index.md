---
title: set_Operator()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Znak operatora Nary. Na przykład: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) metoda


Znak operatora Nary. Na przykład: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## Uwagi


Przykład: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Zobacz także

* Klasa [IMathNaryOperatorProperties](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)