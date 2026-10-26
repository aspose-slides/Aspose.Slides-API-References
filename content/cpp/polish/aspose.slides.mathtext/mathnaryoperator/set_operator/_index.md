---
title: set_Operator()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Znak operatora Nary. Na przykład: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) metoda

Znak operatora Nary. Na przykład: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Uwagi

Przykład:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Zobacz także

* Klasa [MathNaryOperator](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)