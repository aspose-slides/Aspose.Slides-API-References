---
title: get_Operator()
second_title: Referência da API Aspose.Slides para C++
description: "Caractere do operador n-ário Por exemplo: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() método


Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Ver também

* Classe [MathNaryOperator](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)