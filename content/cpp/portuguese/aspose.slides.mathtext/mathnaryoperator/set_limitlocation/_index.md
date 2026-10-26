---
title: set_LimitLocation()
second_title: Referência da API Aspose.Slides para C++
description: A localização dos limites (subscrito e sobrescrito)
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) método

A localização dos limites (subscrito e sobrescrito)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Observações

Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Veja também

* Enumeração [MathLimitLocations](../../mathlimitlocations/)
* Classe [MathNaryOperator](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)