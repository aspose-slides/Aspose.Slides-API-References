---
title: set_Operator()
second_title: Aspose.Slides para C++ Referência da API
description: "Caractere de Operador Nário Por exemplo: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) método


Caractere do Operador N-ário Por exemplo: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Veja Também

* Classe [MathNaryOperator](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)