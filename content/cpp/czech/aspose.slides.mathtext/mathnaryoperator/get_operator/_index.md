---
title: get_Operator()
second_title: Aspose.Slides pro referenci API C++
description: "Znak Nary operátoru Například: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() metoda


Znak Nary operátoru Například: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Viz také

* třída [MathNaryOperator](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)