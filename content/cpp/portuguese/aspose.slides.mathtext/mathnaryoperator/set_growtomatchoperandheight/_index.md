---
title: set_GrowToMatchOperandHeight()
second_title: Referência da API Aspose.Slides para C++
description: O caractere do operador cresce verticalmente para corresponder à altura do operando
type: docs
weight: 105
url: /pt/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) método


O caractere do operador cresce verticalmente para corresponder à altura do operando

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Ver também

* Classe [MathNaryOperator](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)