---
title: set_LimitLocation()
second_title: Aspose.Slides para C++ Referência da API
description: A localização dos limites (subscrito e sobrescrito)
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) método

A localização dos limites (subscrito e sobrescrito)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Observações

Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Ver também

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Classe [IMathNaryOperatorProperties](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)