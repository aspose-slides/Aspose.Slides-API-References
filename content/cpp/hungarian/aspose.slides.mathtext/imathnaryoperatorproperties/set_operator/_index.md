---
title: set_Operator()
second_title: Aspose.Slides C++ API Referencia
description: "Nary operátor karakter Például: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) metódus


Nary operátor karakter Például: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## Megjegyzések


Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Lásd még

* Osztály [IMathNaryOperatorProperties](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)