---
title: get_Operator()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Znak operatora Nary Na przykład: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() metoda


Znak operatora Nary Na przykład: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Uwagi


Przykład: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Zobacz również

* Klasa [MathNaryOperator](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)