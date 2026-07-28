---
title: get_Operator()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Znak operatora n-ary. Na przykład: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() metoda

Znak operatora n-ary Na przykład: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
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