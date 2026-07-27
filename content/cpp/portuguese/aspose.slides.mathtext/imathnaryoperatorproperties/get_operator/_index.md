---
title: get_Operator()
second_title: Aspose.Slides para C++ Referência da API
description: "Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() método


Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Veja Também

* Classe [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)