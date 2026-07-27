---
title: set_Operator()
second_title: Referência da API Aspose.Slides para C++
description: "Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) método


Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Ver também

* Classe [IMathNaryOperatorProperties](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)