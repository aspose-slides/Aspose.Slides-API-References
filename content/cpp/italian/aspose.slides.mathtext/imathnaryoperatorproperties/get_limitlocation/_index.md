---
title: get_LimitLocation()
second_title: Aspose.Slides per C++ Riferimento API
description: La posizione dei limiti (indice e esponente)
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() metodo

La posizione dei limiti (indice e esponente)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Osservazioni


Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Vedi anche

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Classe [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)