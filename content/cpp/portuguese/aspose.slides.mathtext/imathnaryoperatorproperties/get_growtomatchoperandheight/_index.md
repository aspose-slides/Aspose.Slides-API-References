---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides para C++ Referência da API
description: Caractere do Operador cresce verticalmente para corresponder à altura do operando
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() método

Caractere do Operador cresce verticalmente para corresponder à altura do operando

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## Observações

Exemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Ver também

* Classe [IMathNaryOperatorProperties](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)