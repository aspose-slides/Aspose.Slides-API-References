---
title: get_GrowToMatchOperandHeight()
second_title: Referência da API Aspose.Slides para C++
description: O caractere do operador cresce verticalmente para corresponder à altura do operando
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() método


O caractere do operador cresce verticalmente para corresponder à altura do operando

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Veja Também

* Classe [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)