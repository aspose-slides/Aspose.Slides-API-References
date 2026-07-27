---
title: get_LimitLocation()
second_title: Aspose.Slides para C++ Referência da API
description: A localização dos limites (subscrito e sobrescrito)
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() método

A localização dos limites (subscrito e sobrescrito)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Observações

Exemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Veja Também

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Classe [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)