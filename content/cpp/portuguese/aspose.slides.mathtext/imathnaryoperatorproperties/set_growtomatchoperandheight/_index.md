---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides para C++ Referência da API
description: O caractere do operador cresce verticalmente para corresponder à altura do seu operando
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) método

O caractere do operador cresce verticalmente para corresponder à altura de seu operando

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
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