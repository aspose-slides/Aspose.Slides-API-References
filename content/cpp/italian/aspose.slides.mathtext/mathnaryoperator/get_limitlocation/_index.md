---
title: get_LimitLocation()
second_title: Riferimento API di Aspose.Slides per C++
description: La posizione dei limiti (indice e apice)
type: docs
weight: 66
url: /it/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() metodo

La posizione dei limiti (indice e apice)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Osservazioni

Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Vedi anche

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Classe [MathNaryOperator](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)