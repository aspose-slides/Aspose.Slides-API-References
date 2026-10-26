---
title: get_Operator()
second_title: Aspose.Slides pro C++ API Reference
description: "Znak N-ary operátoru Například: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() metoda


Znak N-ary operátoru Například: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Poznámky


Příklad:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Viz také

* Třída [IMathNaryOperatorProperties](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)