---
title: set_Operator()
second_title: Aspose.Slides for C++ API referencia
description: "Nary operátor karakter Például: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) metódus

Nary operátor karakter Például: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Megjegyzések

Példa:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Lásd még

* Osztály [MathNaryOperator](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)