---
title: get_Operator()
second_title: Aspose.Slides for C++ API Referencia
description: "Nary operátor karakter Például: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() metódus


Nary Operátor karakter Például: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Megjegyzés


Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Lásd még

* Osztály [MathNaryOperator](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)